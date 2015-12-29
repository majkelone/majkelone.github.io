---
layout: post
title: A Fortnight Later
date: September 15, 1880
--- 

 A fortnight later, by excellent good fortune, the doctor gave one of his pleasant dinners to some five or six old cronies, all intelligent, reputable men and all judges of good wine; and Mr. Utterson so contrived that he remained behind after the others had departed. This was no new arrangement, but a thing that had befallen many scores of times. Where Utterson was liked, he was liked well. Hosts loved to detain the dry lawyer, when the light-hearted and loose-tongued had already their foot on the threshold; they liked to sit a while in his unobtrusive company, practising for solitude, sobering their minds in the man's rich silence after the expense and strain of gaiety. 

 To this rule, Dr. Jekyll was no exception; and as he now sat on the opposite side of the fire -- a large, well-made, smooth-faced man of fifty, with something of a stylish cast perhaps, but every mark of capacity and kindness -- you could see by his looks that he cherished for Mr. Utterson a sincere and warm affection.

 {% highlight html %}
<html>
  <head>
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />

    <title>{{ site.title }}</title>

    <link rel="stylesheet" href="{{ site.baseurl }}/css/bootstrap.css">
    <link rel="stylesheet" href="{{ site.baseurl }}/css/custom.css">
    <link href='https://fonts.googleapis.com/css?family=Open+Sans:400, 300, 300italic, 400italic, 600' rel='stylesheet' type='text/css'>

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