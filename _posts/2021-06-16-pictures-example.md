---
layout: post #Do not change.
category: [design] #One, more categories or no at all.
title:  "Photos and pictures"
date:   2021-06-16 10:05:42 +0200
author: jekyll #Author's nick.
#nextPart: _posts/2021-01-30-example.md #Next part.
prevPart: _posts/2021-06-16-syntax-example.md #Previous part.
#og_image: assets/example.png #Open Graph preview image.
og_description: "Various picture examples." #Open Graph description.
fb_app_id: example
---

The simplex supports not only embedding pictures but also includes a lightbox plugin. Read the post and check out various examples.

## Dogs

Try to click on the following picture:

<a href="/assets/img/posts/doggo1.jpg" data-lity>
  <img src="/assets/img/posts/doggo1_thumb.jpg"/>
</a>

You see? A big doggo appeared.

---

Images can be centered:

<a href="/assets/img/posts/doggo2.jpg" data-lity class="sx-center">
  <img src="/assets/img/posts/doggo2_thumb.jpg"/>
</a>

---

You don't have to use the lightbox feature. In that case, simply use markdown image tag:

![A picure without lightbox](/assets/img/posts/doggo1_thumb.jpg)

---

There also can be a simple description under the picture:


<div class="sx-center">
    <div class="sx-picture">
    <a href="/assets/img/posts/doggo2.jpg" data-lity>
        <img src="/assets/img/posts/doggo2_thumb.jpg"/>
    </a>
    <span class="sx-subtitle">My picture description.</span>
    </div>
</div>

## Attributions
The first dog picture by [Pauline Loroy](https://unsplash.com/photos/U3aF7hgUSrk).
The second dog picture by: [Marliese Streefland](https://unsplash.com/photos/2l0CWTpcChI).