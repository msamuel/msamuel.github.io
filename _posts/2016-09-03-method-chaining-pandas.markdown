---
layout: post
title:  "Method Chaining in Pandas"
date:   2016-09-03 14:40:57 -0500
---

The Pipe function allows one to combine operations sequentially. This works the same as in Linux. In short, your command line skills transfer directly. This approach doesn't replace the need for a workflow manager but serves well for small to medium single-machine tasks. For example, one can perform ETL on data using Pandas data frame. The user-defined function can be used over and over. The syntax is simple. I have [an example](https://github.com/msamuel/hacks-pandas/blob/master/method_chaining.ipynb "Method Chaining") Jupiter notebook.

<<<<<<< HEAD
I have [an example](https://github.com/msamuel/hacks-pandas "Method Chaining") Jupiter notebook. 
=======
Pandas.pipe:

{% highlight python %}
(df.pipe(h)
   .pipe(g, arg1=a)
   .pipe(f, arg2=b, arg3=c)
){% endhighlight %}
>>>>>>> 95a4bb13b82be195a0ae1121ad2d07c7cba74127

Happy Pythoning.

