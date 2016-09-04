---
layout: post
title:  "Method Chaining in Pandas"
date:   2016-09-03 14:40:57 -0500
---

The Pipe function allows one to combine operations sequentially. For example, one can perform ETL on Pandas data frame is a single task.

Pandas.pipe:

{% highlight python %}

(df.pipe(h)

   .pipe(g, arg1=a)
   .pipe(f, arg2=b, arg3=c)
){% endhighlight %}
I have [an example](https://github.com/msamuel/hacks-pandas "Method Chaining") Jupiter notebook. 
Happy Pythoning.

