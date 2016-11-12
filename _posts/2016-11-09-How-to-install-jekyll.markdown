---
layout: post
title:  "How to install Jekyll on Windows!"
date:   2016-07-19 11:49:45 +0200
categories: jekyll update
---
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/


Install Jekyll o Windows:
First we need to install Ruby on the machine. How to do that?
- Download RubyInstaller from RubyInstaller.org
- Download the actual file and corresponding Dev Kit and extract it to a DevKit folder
- Install RubyInstaller and add it to the Path
- Open command windows and navigate to the DevKit folder and run the command as per below

{% highlight ruby %}
ruby dk.rb init
{% endhighlight %}
