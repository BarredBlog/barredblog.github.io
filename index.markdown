---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
carousels:
  - images: 
    - image: /Media/IMG_8183.jpg
    - image: /Media/IMG_9209.jpg
    - image: /Media/IMG_7686.jpg
  - images: 
    - image: /Media/IMG_8183.jpg
    - image: /Media/IMG_9209.jpg
    - image: /Media/IMG_7686.jpg
---
{% include carousel.html height="50" unit="%" duration="7" number="1" %}
{% include carousel.html height="50" unit="%" duration="7" number="2" %}
{% include image-gallery.html folder="/Media" %}
