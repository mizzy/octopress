---
layout: post
title: "Rakuten tag plugin for Jekyll"
date: 2012-03-04 22:37
comments: true
categories: 
---

I've wrote [Rakuten tag plugin for Jekyll](https://github.com/mizzy/jekyll-plugins/blob/master/rakuten_tag.rb).

You can use this plugin like this.

	{% raw %}{{ "nikondirect:10000349" | rakuten_large_image }}{% endraw %}

{{ "nikondirect:10000349" | rakuten_large_image }}

	{% raw %}{{ "nikondirect:10000349" | rakuten_medium_image }}{% endraw %}

{{ "nikondirect:10000349" | rakuten_medium_image }}

	{% raw %}{{ "nikondirect:10000349" | rakuten_small_image }}{% endraw %}

{{ "nikondirect:10000349" | rakuten_small_image }}

	{% raw %}{{ "nikondirect:10000349" | rakuten_link_image }}{% endraw %}

{{ "nikondirect:10000349" | rakuten_link }}
