---
title: Basic Post
description: 
published: true
date: 2024-05-03T05:07:46.072Z
tags: 
editor: markdown
dateCreated: 2024-05-03T05:07:46.072Z
---

> This is a great quote. &mdash; [Albert Einstein](https://es.wikipedia.org/wiki/Albert_Einstein)

![](/images/probabilistic_logic_learning.jpg)
*Figure 1: Probabilistic Logic Learning as the intersection of Probability, Logic, and Learning. (Image source: [De Raedt and Kersting, 2003](https://www.researchgate.net/publication/2878094_Probabilistic_Logic_Learning))*

<!--more-->


You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

<iframe src="https://www.desmos.com/calculator/ocouu4910y?embed" width="740px" height="500px" style="border: 1px solid #ccc" frameborder="0"></iframe>

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

----


Un poco de matemática

$$
\begin{aligned}
& \int p(x)dx = \int \pi(z)dz = 1 \scriptstyle{\text{   ; Definition of probability distribution.}}\\
& p(x) = \pi(z) \left\vert\frac{dz}{dx}\right\vert = \pi(f^{-1}(x)) \left\vert\frac{d f^{-1}}{dx}\right\vert = \pi(f^{-1}(x)) \vert (f^{-1})'(x) \vert
\end{aligned}
$$

****

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

<iframe src="https://www.desmos.com/calculator/ocouu4910y" width="740px" height="500px" style="border: 1px solid #ccc" frameborder="0"></iframe>

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
