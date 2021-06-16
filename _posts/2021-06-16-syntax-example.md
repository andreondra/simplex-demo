---
layout: post #Do not change.
category: [programming, cpp] #One, more categories or no at all.
title:  "Syntax highlighting example"
date:   2021-06-16 10:05:42 +0200
author: jekyll #Author's nick.
nextPart: _posts/2021-06-16-pictures-example.md #Next part.
prevPart: _posts/2021-06-16-welcome-to-jekyll.md #Previous part.
#og_image: assets/example.png #Open Graph preview image.
og_description: "Various syntax highlighting examples." #Open Graph description.
fb_app_id: example
---

In this post we will have a look at some syntax highlighting abilities.

Here you can see a very simple C++ code snippet:
{% highlight cpp %}
template <class type>
class Vector{

    private:
        type *data;
        size_t used;
        size_t capacity;

    public:
        Vector(size_t elemCount){

            data = new type[elemCount];
            capacity = elemCount;
            used = 0;
        }
        ~Vector(){
            delete[] data;
        }
};
{% endhighlight %}

The simplex support all the languages supported by Jekyll. For example, bash commands can be highlighted as well:
{% highlight bash %}
bundle exec jekyll serve --force-polling
{% endhighlight %}

You can also create your own highlighting palletes! See [simplex readme](https://github.com/andreondra/jekyll-theme-simplex).

The simplex also includes some simple buttons, which can be used for example at the end of the tutorial:
<div class='sx-button'>
  <a href='https://www.example.com/' class='sx-button__content red'>
    <img src='/assets/img/icons/down_arrow.svg'/>Download the source
  </a>
</div>
