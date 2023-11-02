---
title: "[000] How to Contribute?"
weight: 0
readingtime: 60
# aliases: ["/first"]
tags: ["tutorial", "doc"]
author: "赵绪锋"
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: true
description: "This tutorial provides useful documents to contribute talks and update website."
# canonicalURL: "https://canonical.url/to/page"
disableHLJS: false # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: false
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
pass: true
cover:
    image: "" # image path/url
    alt: "Tutorial" # alt text
    caption: "" # display caption under cover
    relative: true # when using page bundles set this to true
    hidden: true # only hide on current single page
---

# How to Join

- Time: (UTC +01:00) Europe/Berlin, Sunday, 17:00-18:00
- Location: Join online with [Zoom link](https://uni-hamburg.zoom.us/j/65464960709?pwd=VGRGZW4vQkg5U2U1RkdQaFk5Tm5MUT09), or offline in F-229, Informatikum.

# How to Update this Website with New Entry

This webpage is powered by Github pages. Any changes will be done within [this github repository](https://github.com/informatikumtalk/informatikumtalk.github.io). 
- Feel free to fork and create PR to update.
- If you are already a collaborator, you can directly update the content in-position.

```python
git clone <THIS_REPO>
cd <THIS_repo>
cd content/talks
```

Under `content/talks` folder create a new directory with `index.md` to maintain information (just like previous talks folders; it is more easier to duplicate a previous example and modify the `index.md` file).

#### Basic Information
#### Calendar

Use https://calndr.link/ to create calendar link.

#### Refresh

Upon any changes pushed to github, this webpage will automatically re-deploy with Github Actions. Usually it takes about 3 min to refresh. So it is recommended to edit and examine the timely refresh locally first before any push.

# How to Edit and Deploy Locally

It is powered by [Hugo](https://github.com/gohugoio/hugo), so one has to configure Hugo and launch server with command `hugo server`.