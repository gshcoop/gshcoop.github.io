---
layout: post
title: "Our Home in Ibrox"
date: 2025-08-06 09:00:00 +0100

image: /media/2025/08/DSC_02061.jpg

---

# Our Home in Ibrox

Two of our members are now living in our beautiful Home in Ibrox, Glasgow, just a short journey by Bike, Bus or Subway from 4 of the West of Scotland's top universities, and the city's many colleges.

Want to live with us? Apply online at [https://forms.gle/y4CvageWWfgXfbQE6](https://forms.gle/y4CvageWWfgXfbQE6).

{%- assign images = site.static_files | where_exp:"image", "image.path contains '/media/2025/08/flat_photos'" -%}
{% for image in images%}
- ![Photo of the flat]({{ image.path | absolute_url }})
{% endfor %}