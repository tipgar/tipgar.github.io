---
layout: post
title: "How to search on multi fields in Elastic"
modified:
categories: blog
excerpt:
tags: []
author: van_pham
image:
  feature:
date: 2015-12-12T15:39:55-04:00
---
{% highlight ruby %}
{
  "multi_match" : {
    "query":    "Garlicman",
    "fields": [ "title", "first_name" ] 
  }
}
{% endhighlight %}

OR
{% highlight ruby %}
{
  "multi_match" : {
    "query":    "Garlicman",
    "fields": [ "title", "*_name" ] 
  }
}
{% endhighlight %}