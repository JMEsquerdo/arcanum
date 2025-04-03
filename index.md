---
layout: landingpage # default
title: Arcanum Caelum
header_type: splash
header_img: "https://images.unsplash.com/photo-1545290614-5ceedf604139?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1200&q=60"
# header_type: hero
subtitle: Wiki
---

{% assign externalgallery = "
https://picsum.photos/seed/10/600/1200,
https://picsum.photos/seed/20/800/500,
https://picsum.photos/seed/30/900/1200,
https://picsum.photos/seed/40/900/1300,
https://picsum.photos/seed/50/750/325,
https://picsum.photos/seed/60/600,
https://picsum.photos/seed/70/700/500" | split: "," %}

{% include_cached snippets/masonry.html external=externalgallery links=externalgallerylinks %}