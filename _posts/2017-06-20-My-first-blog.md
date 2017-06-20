---
layout: default
title:  "My first blog post"
title: My first blog post
description: Just hello world blog post, nothing special...
date:   2017-06-20 15:50:01 -0600
categories: personal
---

Nothing here yet ! Lorem ipsum blah blah ... :smile:

{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}
