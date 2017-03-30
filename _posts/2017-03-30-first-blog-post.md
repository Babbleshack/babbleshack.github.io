---
layout: post
title: "My first post"
date: 2017-03-30
catergories: learning
---

# First post
This is the first post I have made on this blog. 

This blogs will maintain a directory of my learnings, whether that is Software, Electronics or outdoor activities. 

## Code

{% highlight ruby linenos %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}

