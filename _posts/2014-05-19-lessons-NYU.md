---
layout: post
title:  "Lessons learned from NYU"
date:   2014-05-19 10:49:47
image: "/img/nyu-2014.jpg"
image-width: "900"
image-height: "500"
categories: welcome jekyll
---

And just like that, it's over. 
--------------
Three final papers. Two presentations. One showcase. One final exam. Zero courses left to take. In a couple of hours I'll be donning my purple robe and joining the other 99 computer science graduates at Lincoln Center. I'm in a reflective mood, and I'd like to share, in no particular order, some of the things I learned while at NYU.

- Write proper tests for your code! If you don't it will seem to run well - until exactly 1am the day before it is due, when you decide to try it out on some toy input.

- Reading about something is all good and nice, but it's the doing that teaches. nothing will teach you functional programming like implementing DFS in SML/NJ.

- Machine learning is awesome. Deep learning is magic. [Seriously][DL].

- If you designate an array as being volatile, only the pointer is actually volatile. This means that any updates to the array are NOT volatile. A hack to get around this is to reassign the pointer: array = array.

- Concurrency is hard.

- Good variable names are more important than lengthy comments.

- Read the Google papers. Especially [this one][g2]. Oh, and [this one][g1].

- Try to pick project partners carefully. It is better to pick someone smart and hardworking than someone fun.

- Speaking well is important. It's better to leave details unmentioned than to risk confusing your audience.

- Presentations and posters are roadmaps, not actual papers. If it doesn't fit on the page with default font-size, you're writing too much.

- If you have the option to use an external library - use it. Otherwise you'll end up spending weeks debugging your graph implementation rather than solving the problem you set out to solve.

- Skim Hacker News every day, but only pick 1-2 articles to actually read. you probably have more important things to do.

- Everyone non-technical has a startup idea they want to talk to you about. When you need technical people to join you they already have jobs or their own startup.

- Always be learning something outside of CS. Maybe music. or french.

- Use GitHub religiously, even if working alone. You never know when you might find yourself without your laptop or make a huge boo-boo.

- Pick the right tool for the job. Python or Unix for file manipulation, Java/C++ for heavy lifting, Python or Node.js for web, Scala for concurrent applications. C is almost never the right tool.

- The three courses that changed the way I look at software and computers: Fundamental Algorithms, Production Quality Software, and Foundations of Machine Learning.


[DL]: http://cilvr.nyu.edu/doku.php?id=software:overfeat:start
[g1]: http://research.google.com/archive/mapreduce.html
[g2]: http://infolab.stanford.edu/~backrub/google.html
