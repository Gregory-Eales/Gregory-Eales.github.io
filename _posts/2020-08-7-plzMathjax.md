---
layout: post
tags: welcome examples
published: true
---
---
layout: post
mathjax: true
comments: true
title:  "Adding MathJax to a GitHub Pages Jekyll Blog"
date:   2016-08-21 23:41:54 +0000
categories: github jekyll
---

When $$a \ne 0$$, there are two solutions to $$ax^2 + bx + c = 0$$ and they are

$$x_1 = {-b + \sqrt{b^2-4ac} \over 2a}$$

$$x_2 = {-b - \sqrt{b^2-4ac} \over 2a} \notag$$

<!--more-->

You need set `mathjax: true` in the *_config.yml* or the markdown’s front matter to **enable** it.
{:.warning}

**After MathJax enabled**, you can set `mathjax_autoNumber: true` to have equations be numbered automatically, You can use `\notag` or `\nonumber` to prevent individual equations from being numbered.
{:.info}

[Documentation](https://tianqi.name/jekyll-TeXt-theme/docs/en/markdown-enhancements#mathjax)

**markdown:**

```tex
When $$a \ne 0$$, there are two solutions to $$ax^2 + bx + c = 0$$ and they are
$$x_1 = {-b + \sqrt{b^2-4ac} \over 2a}$$
$$x_2 = {-b - \sqrt{b^2-4ac} \over 2a} \notag$$
```

**front matter:**

    ---
    ...
    mathjax: true
    mathjax_autoNumber: true
    ---
