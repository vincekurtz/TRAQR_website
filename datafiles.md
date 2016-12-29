---
layout: page
title: Datafiles
permalink: "/datafiles/"
---

Raw (JSONP) data files are stored on this page.

For example, `fake_data.js` contains randomly generated data points scattered across the county. 
It's what's currently displayed on the [map](../map).

### Files:
{% directory path: datafiles %}
  <a href="../{{ file.url }}" >{{ file.name }}</a>
{% enddirectory %}
