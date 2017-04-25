Hello friends, how has your week been? 😊

In last week's introduction I shared what I think it means to be a "software craftsman". I also mentioned that the titles of software craftsman and software engineer are often misused.

I realised I didn't touch on **what it means to be a software engineer**, and I'd like to do so today.

Engineers all over the world, be them civil, mechanic, electrical are a category of people that **applies the scientific process to the task of "building things"**.

Engineers **make plans**, and then **use mathematical models** to verify that their design are good for the use case of what they're producing.

They also work on a set of **known best practices** and are regulated by commissions.

That's in contrast to most of the software projects I've been involved with. More often than not we software developers are not very scientific in building our programs.

Because software is "soft" there are many different ways of achieving the same result. This is can sometimes be a problem. I'm sure you too have had to deal with projects with no architecture at all, than nevertheless where working and therefore had to be slowly fixed, if possible.

If we really want to call ourselves software engineers then we should aim to be more scientific in our process and more rigorous in what we do.

An actionable tip on how to do this: research design patterns and software architectures models, and apply them rather than whipping up custom implementations on every project.

<br/><hr/><br/>

### [Request Behaviours](http://khanlou.com/2017/01/request-behaviors)

Since we spoke of patterns, [Soroush Khanlou](https://twitter.com/khanlou) shows how to use the [decorator pattern](https://en.wikipedia.org/wiki/Decorator_pattern) to add _behaviours_ to URL requests in Swift.

The idea behind behaviours is to encapsulate side effects that a request should perform, like showing the network activity indicator or injecting an authentication header into each request sent, into objects that can then passed to a "generic" URL request performer. This allows us to separate concerns and easily test them.

### [Measuring software engineering competency](http://www.savvyclutch.com/measuring-software-engineering-competency/)

[Bogdan Frankovskyi](https://github.com/Ferroman) builds on top of [The Joel Test](https://www.joelonsoftware.com/2000/08/09/the-joel-test-12-steps-to-better-code/) and presents a list of questions with yes/no answers and an associated scoring system.

I like the premise of the post:

> Why do we want to measure our competency? Well… because we want to improve. And we have to!

I think going through these questions is a good exercise to take a step back and look at your team from the outside.

It doesn't really matter what score you have now, but what score you will have six months from now. _My team's score is 1 by the way_.

### [Deep Dive Into iOS Automation At Grab - Integration Testing](http://engineering.grab.com/deep-dive-into-ios-automation-at-grab-integration-testing)

[Sun Xiangxin](https://github.com/xiangxin) talks us through who her team's at Grab does integration testing, and why they choose Xcode Server to do so.

### [Updating the GOV.UK Continuous Integration environment](https://gdstechnology.blog.gov.uk/2017/02/10/updating-the-gov-uk-continuous-integration-environment/)

Another infrastructure and integration post. [Laura Martin](https://twitter.com/surminus) shares how her team is revamping the GOV.UK infra, starting from their CI setup, using Puppet and Jenkins.

I think the fact that a government agency is so open about their software stack and [has part of it open source](https://github.com/alphagov) is remarkable, regardless of what's your opinion on Jenkins 😜.

<br/><hr/><br/>
