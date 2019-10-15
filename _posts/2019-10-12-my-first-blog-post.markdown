---
layout: post
title:  "My First Blog Post!"
date:   2019-10-12 17:03:09 -0600
categories: jekyll update
---

# Introduction
This is my ery first blog post. I will be experimenting with features of [jekyll][jekyll_link], the tool that I am using to make blogging a bit easier. Special shout out to [Github pages][gh_link], without which, I wouldn't really know how to create a website, or host it, or any of that.

# A Bit About Me
I am a fourth year computing science student at the University of Alberta. One thing you will quickly learn about me is that I am an avid swing dancer. I currently teach begginner lessons with [Swing Out Edmonton][soe_link], and am a part of the Minnie Dippers dance team. If you are in the Edmonton area, you should really check it out! 

Some of my other hobbies include:  
  * Playing guitar (acoustic, and primarily for myself)
  * Boardgames (I am working on a sizable collection. My latest addition is _Photosynthesis_.)
  * Skateboarding (Yeah, I'm pretty cool. I use a penny board to get to my bus)

# Why is there so many weird things on this post?
I am very new to markdown, and html/javascript, so this page will serve as a bit of a reference for me. That is why I will include a random picture of

![image](/assets/broccoli.jpg)

<!-- 
<img src="/assets/broccoli.jpg" alt="Picture of Broccoli">
-->

brocoli.  
Weird, I know.

Another create fact that I've learned about markdown and html, is that it can work with Latex formatting, using [MathJax][mj_link]. Using that, we can get all sorts of equations, like:

{% raw %}
$$ \frac{\sum_{i=0}^N x_i^i}{\sqrt{5e}} $$
{% endraw %}

\\[ \frac{1}{2} \\]

With a different choice of syntax markers, we end up with:

$$ \frac{1}{3} $$
$$
\int_0^\infty e^{-x^2}\,dx = \frac{\sqrt{\pi}}{2}.
$$

Jekyll also has some nice, built in syntax highlighting

{% highlight python %}
# Python code
def print_hi(name):
  print("Hi " + name)
{% endhighlight %}

[jekyll_link]: https://jekyllrb.com/
[gh_link]: https://pages.github.com
[mj_link]: https://www.mathjax.org/
[soe_link]: https://www.swingoutedmonton.com/
