issues_folder = 'issues'

desc "Generate the HTML code for the latest issue, and copy it to the clipboar"
task :build do
  latest = Dir["#{issues_folder}/*.md"].last
  sh "redcarpet --smarty header.md #{latest} footer.md | pbcopy"
  puts "👍 HTML code for #{latest} copied to clipboard"
end

desc "Create the markdown source for a new issue"
task :new do
  count = '%03d' % Dir["#{issues_folder}/*.md"].length
  path = "#{issues_folder}/mokacoding-weekly-#{count}.md"
  sh "cp content-template.md #{path}"
end
