# TinyLazyLoad

A tiny lazy load script using vanilla js + intersection observer.

See demo here: https://metinsaylan.github.io/tinylazyload/


## Usage

1. Add `lazy` class to target element
2. Define source using `data-src` attribute for images and iframes
3. Define source using `data-src-background` attribute for background images

```

<img class="lazy" src="" data-src="https://picsum.photos/id/109/1200/480/">

<div class="lazy" data-src-background="https://picsum.photos/id/1051/1200/480/"></div>

<iframe width="560" height="315" src="" class="lazy" data-src="https://www.youtube.com/embed/HG92yUC59Nk"></iframe>

```

