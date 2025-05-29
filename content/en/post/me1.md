---
author: Adnan Baig 
title: My metadata with my footer and an image & example post.
date: 2025-04-01
description: How to add badges to your posts
tags: 
    - Quran
    - Memorisation
    - Hifz
    - Hafiz
categories:
    - experiments

#badges:
#    google:
#        subject: Google Drive
#        status: Google drive folder.
#        icon: Google
#        url: https://drive.google.com/drive/u/2/folders/1MxD9Dm6SYGsTXdnVrBTV0qstPYqqrQ9M
#        color: grey
#        label: ""

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


Everythings worked fine so far so I've no idea what it is. I might just remove and re add my posts if this file renders fine.

<!--more-->

Does this image mess the scaling up?




# How to use it

```go-html-template
{{</* 
callout 
    kind="info"
    title="Here's something you should probably know"
    content="Even light has a speed"
*/>}}
```

We have some pre-configured values for `kind`. But it's also possible to [customize](#customized) them!

# Kinds

## Info
{{< callout 
    kind="info"
    title="Here's something you should probably know"
    content="Even light has a speed"
>}}

## Question

{{< callout 
    kind="question"
    title="What is it?"
    content=""
>}}

Note that `content` can be empty.

## Success

{{< callout 
    kind="success"
    title=""
    content="The speed of lights is _exactly equal_ to $c$"
>}}

The `title` can be empty, too.

## Alert

{{< callout 
    kind="alert"
    title="Stop messing with me!"
    content="Just tell me the value"
>}}

## Nope

{{< callout 
    kind="nope"
    title="Nope"
    content="You should do some research"
>}}


## Note

{{< callout 
    kind="note"
    title="Research"
    content="The speed of lights is _exactly equal_ to 299,792,458 m/s"
>}}

Feel free to suggest new ones [here](https://github.com/LucasVadilho/heyo-hugo-theme)!

# Customized

You can customize the callout by choosing your own [Font Awesome](https://fontawesome.com/search) icon and color. All you need to do is add `icon` and `color` to the shortcode.

## Example

```
{{</* callout 
    title="Research"
    content="The speed of lights is _exactly equal_ to 299,792,458 m/s"
    icon="fas fa-atom"
    color="linear-gradient(95deg, #9198e5, #e66465)"
*/>}}
```

Will be rendered as:

{{< callout 
    title="Research"
    content="The speed of lights is _exactly equal_ to 299,792,458 m/s"
    icon="fas fa-atom"
    color="linear-gradient(95deg, #9198e5, #e66465)"
>}}

<br>

---

<br>

Thanks for reading this post! Hopefully you enjoyed reading it or at least found it interesting. If you'd like to read more articles like this feel free to follow me on social media using the links on [the homepage](https://peopleofthebook.co.uk) or below.

If you'd like to support my work feel free to share my posts or website on social media. If there's a topic you'd like me to consider feel free to email me at peopleofthebook601@gmail.com

Also, I have a poetry book! It's published [here](https://amzn.eu/d/3nzHMT6) on Amazon and free to read if you're a kindle unlimited subscriber. Kindle unlimited authors get paid based on how many pages are read.

Alternatively you can buy the ebook for £1.99 from the UK site, the prices will vary if you're in a different part of the world.

I'm giving 50% profits to charity: 25% Palestine and 25% to the Uyghur Muslims of Turkestan. A further 25% of profits will go towards other projects i'm working on that will raise more money for people in need.

[*Gmail:* peopleofthebook601@gmail.com](peopleofthebook601@gmail.com)

[*IG:* https://www.instagram.com/peopleofthebook601/](https://www.instagram.com/peopleofthebook601/)

[*Threads:* https://www.threads.net/@peopleofthebook601](https://www.threads.net/@peopleofthebook601)

