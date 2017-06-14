require 'erb'
require 'tmpdir'

issues_folder = 'issues'

desc "Generate the HTML code for the latest issue, and copy it to the clipboar"
task :build do
  latest = Dir["#{issues_folder}/*.md"].last

  number = File.basename(latest, File.extname(latest))
    .split('-')
    .last
    .to_i
    .to_s

  renderer = ERB.new(File.read('header.md.erb'))

  path = Dir.pwd

  Dir.mktmpdir do |tmpdir|
    File.open("#{tmpdir}/header.md", 'w') { |f| f.write(renderer.result(binding)) }
    sh "redcarpet --smarty #{tmpdir}/header.md #{path}/#{latest} #{path}/footer.md | pbcopy"
  end
  puts "👍  HTML code for #{latest} copied to clipboard"
end

desc "Create the markdown source for a new issue"
task :new do
  next_number = '%03d' % (Dir["#{issues_folder}/*.md"].length + 1)
  path = "#{issues_folder}/mokacoding-weekly-#{next_number}.md"
  sh "cp content-template.md #{path}"
  sh "#{ENV['VISUAL']} #{path}"
end
