Hello 😊 Hope you had an happy Easter break 🐰.

Over the course of the week I came across the concept of "software craftsmanship" in a number of places.

In the past I felt like like the word "craftsmanship" was bloated and misused in the context of software development, a bit like the word "engineering". Recently though I changed my mind.

I now think that "craftsmanship" and "engineering" are word that fit very well in our jobs, and what I was seeing as a misuse of them was actually due to some individuals using such titles without embodying the qualities they represent.

**What does it mean to be a software craftsman?**

When hearing the word craftsman my mind pictures to a person doing some sort of manual labour that requires a lot of precision and years of experience, _often wearing classes and one of those work aprons with many pockets_.

The keyword here is **experience**, years of it. To call ourselves software craftsmen we must first realise that **you are not one yet!** It takes many years to master a craft. I have been developing software professionally only since 2011, I am merely an senior apprentice.

Another thing that always accompanies my mental image of a craftsman is that **they have tools**.

Like shoemakers and blacksmiths we too have tools. Our IDE of choice, the terminal, Git, the programming we're currently working with, the many frameworks we use to avoid reinventing the wheel.

To be a software craftsman means to be committed to **master our tools**, and to **be able to choose the right one for the job**.

Finally, I think a distinctive trait of the software craftsman is that they take great pride on what they make, and always strive to get better and better results.

Craftsmanship is a journey that requires being humble and curious, deliberate and focused.

<br/><hr/><br/>

### [🎧 Software Engineering Radio - Dropbox Distributed Storage System](http://www.se-radio.net/2017/03/se-radio-episode-285-james-cowling-on-dropboxs-distributed-storage-system/)

Very fascinating interview with [James Cowling](https://twitter.com/jamesacowling) on why and how Dropbox moved away from Amazon's S3 and built [Magic Pocket](https://blogs.dropbox.com/tech/2016/05/inside-the-magic-pocket/) their own distributed storage system.

Very few of us will ever have to build such a system, but the experience shared by James in this interview goes beyond the technical details of the system, and his full of valuable lessons on how to build software systems, and how to migrate from old to new ones.

Something that really resonated with me is the team's focus on building something simple, as they knew complexity would have inevitably crept in.

### [📝 The Value of Testing](https://j11y.io/general/the-value-of-testing/)

[James Padolesy](https://twitter.com/padolsey) wrote this post a few years ago, but it's contents are still relevant, timeless I'd say.

As developers most of us agree that having tests in our codebase makes it better on many fronts, but how can we frame this in a language that can convince skeptical business owners?

Also note the closing line:

> Tests won’t be the redeeming grace of poor architecture; they complement a well written codebase.

### [📝 Artsy's Technology Stack, 2017](http://artsy.github.io/blog/2017/04/14/artsy-technology-stack-2017/)

A focused dive from [Orta Therox](https://twitter.com/orta) on how the Artsy engineering team is organized, the tech they use, and how they "make the technical and human sides of Artsy businesses work."

It's always interesting to see how other organization works, in particular successful ones. How does Artsy's structure compare to your company one? Is there anything that you could take away from their experience and trial yourself?

### [📝 Why you should co-locate your Xcode tests](https://kickstarter.engineering/why-you-should-co-locate-your-xcode-tests-c69f79211411#.x3ffvhuy4)

[Brandon Williams](https://twitter.com/mbrandonw) makes the case for co-locating the source and tests of your components in the same folder. This is the approach his team at Kickstarter has taken for their ([open-source!](https://github.com/kickstarter/ios-oss)) iOS app, and they "are loving it".

Definitely worth giving it a shot on your next project 👌.

### [📝 You Should Use Static Dates For Your Unit Tests](https://spin.atomicobject.com/2016/12/23/static-dates-unit-tests/)

Yes, you should.

I've been linking to this article by [Andy Peterson](https://spin.atomicobject.com/author/andy-peterson/) in many code reviews recently.

Being bitten by some timezone or DST bug in your software is sort of a rite of passage in the journey of the software developer, but that doesn't mean we shouldn't try our best to avoid these issues.

Using static dates in our tests like Andy suggests is a good step to do so.

<br/><hr/><br/>
