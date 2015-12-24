---
layout: post
title:  "Welcome to Jekyll!"
date:   2015-12-19 02:13:17 +0100
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

{% highlight ruby %}
<html>
  <head>
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />

    <title>{{ site.title }}</title>

    <link rel="stylesheet" href="{{ site.baseurl }}/css/bootstrap.css">
    <link rel="stylesheet" href="{{ site.baseurl }}/css/custom.css">
    <link href='https://fonts.googleapis.com/css?family=Open+Sans:400,300,300italic,400italic,600' rel='stylesheet' type='text/css'>

  </head>


  <body>

    <div class="container">

      <header class="row">
        <div class="col-xs-1 col-md-2">
        </div>
        <div class="col-xs-22 col-md-20 text-center">
          <h1><a href="http://localhost:4000">{{ site.title }}</a></h1>
          <p>{{ site.description }}</p>
          <hr />
        </div>
      </header>

      {{content}}

    </div>

    <script src="{{ site.baseurl }}/js/bootstrap.js"></script>
  
  </body>
</html>
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/