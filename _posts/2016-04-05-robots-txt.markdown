---
layout: post
title:  "Robots.txt"
categories: robots.txt
---

*Robots.txt* is a way to set specific settings for how search engines (and web crawlers) should index your site.
I added it to my site by creating a file called *robots.txt* to the root of my site. Then I simply added the following bit of code:


{% highlight scss %}
User-agent: *
> Disallow: /
{% endhighlight %}


