---
layout: post
title: "Search on multi fields in Elastic"
modified:
categories: blog
excerpt:
tags: [Elastic,search]
author: van_pham
comments: yes
image:
  feature:
date: 2015-12-12T15:39:55-04:00
---

When you want to search for text which maybe in some fields of your Elastic index, you can use following syntax, with value of <strong>query</strong> is the text you wanna search for, and <strong>fields</strong> is an array of string for multiple fields that you wanna search on.

{% highlight ruby %}
{
  "multi_match" : {
    "query":    "Garlicman",
    "fields": [ "title", "first_name" ] 
  }
}
{% endhighlight %}

Wildcards can also be used on your field name, such as <strong>*_name</strong> in below snippet:

{% highlight ruby %}
{
  "multi_match" : {
    "query":    "Garlicman",
    "fields": [ "title", "*_name" ] 
  }
}
{% endhighlight %}