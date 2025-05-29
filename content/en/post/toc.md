---
author: Lucas David Vadilho
title: Table of Contents
date: 2023-08-04
tags: 
    - theme
categories:
    - heyo
showToc: true
---

In {{< theme >}} we can use the sidebar to display a Table of Contents!

<!--more-->

# Introduction

adnan This post is a guide on how to display a Table of Contents in the sidebar.


Born into a Sunni family, I've been learning about and exploring Shia Islam. Here are my thoughts so far.


**Disclaimer:** I am not an expert in religion. I'm not even sure I count as a student of knowlege. I am however seeking knowlege. This is an opinion post not designed to prove one perspective true at the expence of the other.

If I had a choice I would just call myself Muslim. Not Shia, not Sunni, just Muslim. I don't really like the concept of vs in religion at all to be honest. It's like when you watch religious debates, one person on one side and another person opposite, both trying to win arguments and prove they are right and the other person is wrong, often resorting to insults and derogitory speech toward one another.




It probably goes without saying, but the TOC is navigable.

# Methods

1. Add `showToc: true` to your front-matter
2. That's it

## Example

This post has the following front-matter:

```yaml
---
author: Lucas David Vadilho
title: Table of Contents
date: 2023-08-01
showToc: true
---
```

# Heading levels

In `config.toml` we have the configuration for the levels, so it's very easy to customize. By default we start at 1, and end at 6.

```toml
[markup]
    [markup.tableOfContents]
        startLevel = 1
        endLevel = 6
```

# Level 1

## Level 2

### Level 3

#### Level 4

##### Level 5

###### Level 6

If you get this deep you should probably restructure your document (jk).
---
author: Adnan Baig 
title: Shia vs Sunni, why "vs"?
date: 2025-05-25 
description: Are the two sects really **that** different?
tags: 
    - Islam
    - Shia vs Sunni
categories:
    - Religious divergence
#badges:
#    github:
#        subject: GitHub
#        status: Check it on GitHub
#        icon: github
#        url: https://github.com/baigel2/5minutehifz
#        color: grey
 #       label: ""

#    template:
#        flat: false
#        subject: subject
#        status: status
#        label: label
#        color: 000
 #       label_color: pink
 #       icon: awesome
  #      url: https://badgen.net/

---


