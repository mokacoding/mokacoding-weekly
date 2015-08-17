<br/><hr/><br/>

### [Explicit Dependencies for Code with No Surprises](http://www.mokacoding.com/blog/explicit-dependencies/)

Sometimes the idea we get when reading a class interface is different from what is actually going on inside its implementation, for example there could be several hidden dependencies. Making a class dependency explicit in its interface is a useful technique to make the code simpler to understand, and easier to test.

### [iOS Build Infrastructure as Square](https://corner.squareup.com/2015/07/ios-build-infrastructure.html)

If you have followed this newsletter for a while you know that I am a big fan of posts by big companies describing their build infrastructure. This week is [Square](https://squareup.com/au/)'s turn. This is a very detailed post, full of tips, and explaining not only how the _infra_ is setup, but the choices that lead to it.

### [iOS: The One Weird Trick For Testing View Controllers in Swift](http://natashatherobot.com/ios-testing-view-controllers-swift/)

Natasha The Robot took the time to explore on [@modocache](https://twitter.com/modocache)'s talk [Everything You (N)ever Wanted to Know about Testing View Controllers](http://www.slideshare.net/bgesiak/everything-you-never-wanted), and shares good tips on how to write unit tests for `UIViewController` subclasses in a safe way. I think is a good thing to know, but you should keep it as your very last testing card. It is usually better to extract the logic that needs to be tested into a well defined object, and only write _glue code_ in the view controller

<br/><hr/><br/>
