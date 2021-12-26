---
layout: post
title:  "Building a simple DNS for DynDNS resolution"
date:   2021-12-26 11:54:08 +0100
categories: tech
---
When you want to run a homelab, you do have a problem when it comes to IP resolution.
At least in germany you do. Because your home internet connection does only get a temporary IP
from your ISP. This can change when you restart your router or just completely random.

The normal solution for this is a DynDNS service and just use the probably existing option in your router to hit an http endpoint and update some domain to point to your IP address. If it changes it will just update the IP the domain is referencing to.


Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
