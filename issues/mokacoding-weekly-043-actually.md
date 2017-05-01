Hi, hope I'm finding you well 😊.

During the week I've come across a number of long pull requests, 600+ lines long.

The problem with long PRs it becomes **harder to keep the whole change set in your mind**, and to be able to judge whether or not the implementation as a whole makes sense in the context of the codebase.

The longer the diff to review, the **harder it is to stay focused** on it and spot little mistakes.

A long pull request requires a lot of time to be reviewed, and one might be tempted to delay looking at it, to get a quicker task done first, resulting in the feedback loop getting longer.

If I can, I'll suggest an exercise for your week: to try and **write small PRs**. If you need some inspiration on how to do it [this post](http://blog.ploeh.dk/2015/01/15/10-tips-for-better-pull-requests/) has a nice list of tips.

<br/><hr/><br/>

### [📺 The Future of Software Engineering](https://www.youtube.com/watch?v=Tg9D7UE4TyI)

Friend and reader [Sam Ritchie](https://twitter.com/fakesamritchie) pointed this talk by [Glenn Vanderburg](https://twitter.com/glv) to me as a follow up on last week's discussion on what it means to be a software engineer.

Glenn argues that the whole "software is not engineering" idea is based on a flawed understanding of what engineering actually is, and goes on exploring what defines engineering. The talk closes with tips on what to focus on to become better software engineers.

### [📝 Revealing Interfaces](https://michaelfeathers.silvrback.com/revealing-interfaces)

[Michael Feathers](https://twitter.com/mfeathers), author of one of my favourite books [Working Effectively with Legacy Code](https://www.goodreads.com/book/show/44919.Working_Effectively_with_Legacy_Code), shares a technique to simplify large classes that are doing to much by leveraging the compiler in a statically typed language.

Feathers considers a class large when it has more than 15 methods, quite short for some of the projects I worked in 😱.

### [📝 The Wrong Abstraction](https://www.sandimetz.com/blog/2016/1/20/the-wrong-abstraction)

[Sandi Metz](https://twitter.com/sandimetz) explores the risks of using, or rather ending up with, the wrong abstractions in our code, and how to remediate it.

It comes down to us being aware of the [sunken cost fallacy](https://en.wikipedia.org/wiki/Sunk_costs#Loss_aversion_and_the_sunk_cost_fallacy) and not be afraid to introduce a bit of code duplication. Insightful read.

### [📝 A Case For Using Storyboards on iOS](https://medium.cobeisfresh.com/a-case-for-using-storyboards-on-ios-3bbe69efbdf4)

What's your take on Storyboards vs code? I prefer code, which is why I try to get exposed to posts that say the opposite of what I think, just to double check my assumptions are still correct.

[Marin Benčević](https://twitter.com/marinbenc) lists a few reasons why he thinks Storyboards are a good tool to use, even when working in a team.

### [📝 Tales of a Chef Workflow: Cookbook Organization and Maintenance](https://blog.dnsimple.com/2017/04/cookbook_maintenance/)

[Aaron Kalin](https://twitter.com/martinisoft) from [DNSimple](https://dnsimple.com/) shares the practices his team has adopted to maintain Chef coockbooks.

These tips go beyond Chef and can be applied to any codebase.

<br/><hr/><br/>
