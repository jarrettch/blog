---
layout: post
title:  "Time to Start Blogging"
date:   2014-04-14 12:45:00
---

I've decided to actually use my blog for something other than a placeholder, so here we go!

{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}
