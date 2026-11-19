---
title: A theme for Zed
description: I made a dark theme for my editor and put it on GitHub.
---

I never meant to make a theme. I just kept changing one thing at a time — a
warmer accent here, a calmer background there — until it had a name. That name
is Pumpkin Season.

It's a dark theme: cool slate surfaces, ember orange across most of the UI, and
a syntax palette that stays readable late at night. It's also the palette this
blog uses, which is why the two look like they belong together.

<figure>
  <img src="{{ '/assets/images/pumpkin-season-zed.png' | relative_url }}" alt="Pumpkin Season in Zed, showing Python with pink keywords, lime strings and mint functions" width="1500" height="1000" loading="lazy">
  <figcaption>The demo file from the repo, in Pumpkin Season.</figcaption>
</figure>

One caveat up front: there is no light variant. A Zed theme declares an
appearance — dark or light — and this one is dark, so if your system is in light
mode you won't see it in the picker at all. Zed will use its own light theme
instead.

Installing it is one file:

```sh
mkdir -p ~/.config/zed/themes
cp themes/pumpkin-season.json ~/.config/zed/themes/
```

Then `cmd-k cmd-t` and pick Pumpkin Season.

The repo, with the theme, a preview and an install script:
[github.com/PumpkinSeason/zed-pumpkin-season](https://github.com/PumpkinSeason/zed-pumpkin-season).

It's MIT. Take it apart.
