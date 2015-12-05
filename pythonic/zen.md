# Python的哲学
在python命令行中输入import this， 就会打印出一段‘The Zen of Python’的描述:

> The Zen of Python, by Tim Peters
>
> Beautiful is better than ugly.  
> Explicit is better than implicit.  
> Simple is better than complex.  
> Complex is better than complicated.  
> Flat is better than nested.  
> Sparse is better than dense.  
> Readability counts.  
> Special cases aren't special enough to break the rules.  
> Although practicality beats purity.  
> Errors should never pass silently.  
> Unless explicitly silenced.  
> In the face of ambiguity, refuse the temptation to guess.  
> There should be one-- and preferably only one --obvious way to do it.  
> Although that way may not be obvious at first unless you're Dutch.  
> Now is better than never.  
> Although never is often better than *right* now.  
> If the implementation is hard to explain, it's a bad idea.  
> If the implementation is easy to explain, it may be a good idea.  
> Namespaces are one honking great idea -- let's do more of those!  

这就是python的设计哲学，即’python之禅‘，其中文翻译如下：

> python之禅, by Tim Peters
>
> 优美胜于丑陋  
> Beautiful is better than ugly.   
> 明了胜于晦涩  
> Explicit is better than implicit.    
> 简单胜过复杂  
> Simple is better than complex.  
> 复杂胜过凌乱  
> Complex is better than complicated.    
> 扁平胜于嵌套  
> Flat is better than nested.  
> 间隔胜于紧凑  
> parse is better than dense.  
> 可读性很重要  
> Readability counts.  
> 即使假借特例的实用性之名，也不可违背这些规则  
> Special cases aren't special enough to break the rules.  
> 虽然实用性比纯粹性重要    
> Although practicality beats purity.  
> 不要包容所有错误（精准地捕获异常）    
> Errors should never pass silently.    
> 除非你确定需要这样做  
> Unless explicitly silenced.  
> 当存在多种可能时，不要尝试去猜测  
> In the face of ambiguity, refuse the temptation to guess.  
> 而是尽量找一种，最好是唯一种明显的解决方案  
> There should be one-- and preferably only one --obvious way to do it.  
> 虽然这并不容易，因为你不是 Python 之父  
> Although that way may not be obvious at first unless you're Dutch.  
> 做也许好过不做   
> Now is better than never.  
> 但不假思索就动手还不如不做   
> Although never is often better than *right* now.  
> 如果你无法向人描述你的实现，那肯定不是一个好方案  
> If the implementation is hard to explain, it's a bad idea.  
> 如果你很容易向人解释你的实现，那么它很可能是个好方案  
> If the implementation is easy to explain, it may be a good idea.  
> 命名空间是一种绝妙的理念，应当多加利用  
> Namespaces are one honking great idea -- let's do more of those!   

如果说语言是一种工具，那么毫无疑问，不同工具会对思维方式产生不同影响, 也许python程序员大部分有极简主义倾向，讨厌复杂的东西，他们更加关注如何更快地get things done.

python作为一种优雅的工具，有一些独到的优点：

    - 简洁    更少的代码， 更多的事情
    - 库比较多    大量现成的轮子，更快的get things done
    - 语法清晰，可读性高    做一种事情通常只有一种最好的方法

我们应该充分运用这些优点，发挥更高的生产力，接下来的几节将描述致力于简洁性的DRY和KISS原则，以及介绍一些python好用的工具和轮子.
