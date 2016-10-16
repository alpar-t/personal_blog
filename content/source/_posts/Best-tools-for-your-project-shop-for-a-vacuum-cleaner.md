---
title: 'Best tools for your project: shop for a vacuum cleaner'
date: 2016-10-16 07:19:22
tags: [choices, libraries, software]
---

<img style="float:left; padding: 1em;" width="250px" src="../../../../images/vacuum.png">

I think we can all agree that [the best code is no code at all](https://blog.codinghorror.com/the-best-code-is-no-code-at-all/).
The ways to get there are also mostly obvious: keep your code
[DRY](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself), 
only write the code that you will 
[surely need](https://en.wikipedia.org/wiki/You_aren%27t_gonna_need_it), but these are not the only
ways. 
With the proliferation of open source, and the success of
<i class="fa fa-github" aria-hidden="true"></i>[github](https://github.com/) it is easier than ever
to find a software library, framework or tool that you can use to avoid writing large chunks of
code. 
In fact most of the time you are faced with the opposite problem: too many to choose from.
So how do you do it ? 
In this post I'll talk some of my personal approaches.

Truth be told, I used to quickly pick up open source projects without putting much thought into it. 
Sometimes I just want to see something work and consider all else lather, 
other times it's deadlines, or you just don't know how far the project will get and how much this
choice will weight. 
So I did the easiest thing: search, pick the first result and move on.
I could write about the ways in which this was wrong, and how I figured out "why" this choice this
needs to be made, but the "how" has a much more interesting story to it. 

Some time ago, I got an unimaginably difficult task: 
My wife wanted me to look for a new vacuum cleaner. 
My family believes that being an IT professional gives you magic powers over anything that runs on
electricity, I can see trough the circuits and software bits pretty much like the falling
green code [Neo](https://en.wikipedia.org/wiki/Neo_(The_Matrix) sees, so
that design, quality assurance and manufacturing practices became apparent and it's easy to tell why
"stuff ain't working". I surely must be able to fix these too if I really wanted.
Never mind stopping bullets. 
No amount of explanation seems to be able to change this, so I took it upon myself to find the
perfect vacuum.
This wasn't the first, and we were unhappy with all predecessors, so the
pressure was on. 

I took a professional stance, doing research, taking notes, documenting my path, just like I would
with a software project. 
Once I got into it, I could not believe the features and selling points these things had to offer,
shape, color, form factor, engine performance, environmental friendliness, use on carpets vs use on
hard floors, loudness, dust recipients and of course wild price ranges to top it off.

Seems so hard, yet it's so easy. There's one property that's above everything else.
A true "deal breaker", without which you would never consider one. 

Did you figure it out? 

If you didn't, think about what's the primary goal you want to achieve ?
You want a clean house. 
That means that you want it to suck up all dust and dirt, and keep it in the recipient. 
I used the 
[dust re-emission class](https://ec.europa.eu/energy/sites/ener/files/documents/Consumer%20guide%20-%20vacuum%20cleaners%20FIN.pdf)
as my deal breaker. 
It doesn't matter how much dust it sucks in how fast if it pushes it out into the air on the other
end for it to settle all over the place.
It's so obvious that you can not help but wonder why some manufacturers don't even label or
advertise it. 
It's  incredible how narrow the wast field becomes once you filter for the top 
dust re-emission class.
My strategy turned out to be a good one, we are happy with my pick ever since. 

When I think back, I'm aways amazed how long it took me to realize what to look for.
It's not always easy to find the obvious. 

I use the same approach when picking libraries, frameworks
or tools. 
Always find the deal breaker, the one thing you most desperately need to have.
The one thing you won't compromise on.
Use that to narrow the search and decide based on the compromises you would need to make. 
Your logging library should actually make the logs available at all times, 
your code generator should not make you spend more time debugging the results than writing the code
yourself. It doesn't hurt if your ORM can retrieve objects from a database either. 
The list goes on. 
The less common the need you are looking to fill, the harder it will be to find it
and in turn the more likely that you will miss it if not making the time and effort to consider.

I will talk about the compromises and what else to consider in the next post. 




