---
title: "About"
date: 2021-07-05T19:15:03+08:00
draft: false
author: "Law Aritao"
avatar: "/images/bunny.png"
featured_image: "/images/banner.jpg"
---

# This Hugo Theme uses Bulma CSS

To configure the front page, edit the config.toml file:

## Use [params.frontPageHeader] to customize front page header text:

```
[params.frontPageHeader]
frontPageHeader= "Your header"

```

## Change the front page paragraph:

```
[params.frontPageText]
frontPageText = "Your text here."
```

## Edit the call to action button:

```
[params.frontPageButtonText]
text = "Your Call to Action"
url="your URL"
[params.frontPageImage]
url ="URL to your image"
altText= "Your alt text"

```

### Box previews for featured posts!

The front page will display up to nine of your recently featured posts. Use the tag "featured" in the front matter to have it show up in the front page. You may change the default number in line 27 of your theme's layouts>index.html file:

```
27  {{ range last 9 .Site.Taxonomies.tags.featured }}

```

#### Change the number above from 9 to your preferred limit.
