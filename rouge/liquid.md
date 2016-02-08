---
title: Liquid
---

{% highlight ruby %}
# Ruby knows what you
# mean, even if you
# want to do math on
# an entire Array
cities  = %w[ London
              Oslo
              Paris
              Amsterdam
              Berlin ]
visited = %w[Berlin Oslo]

puts "I still need " +
     "to visit the " +
     "following cities:",
     cities - visited
{% endhighlight %}



## Raw Escape

Adds extra leading and trailing line in pre block?

Standard code block (w/ raw):

```
{% raw %}
{% highlight ruby %}
puts "Hello, World!"
{% endhighlight %}
{% endraw %}
```


Highlighter code block (w/ raw):

{% highlight ruby %}
{% raw %}
{% highlight ruby %}
puts "Hello, World!"
{% endhighlight %}
{% endraw %}
{% endhighlight %}

