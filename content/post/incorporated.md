---
title: Hugo Incorporated Features
description: "What's in the box"
date: 2014-06-19 11:24:00+07:00 

coverimage: blog-cover.jpg

excerpt: "Incorporated provides a great typography, responsive design, author details, semantic markup and more."

authorname: Nicholas Whittier
authorlink: http://imperialwicket.com
authortwitter: nw_iw
authorgithub: imperialwicket 
authorbio: Some dude.
authorimage: faces.jpg
---

Incorporated provides a great typography, responsive design, author details, semantic markup and more.

You can set customize post covers, and other things directly in the post front matter:

{{% highlight yaml %}}
title: Hugo Incorporated Features
description: "What's in the box"
date: 2014-06-19 11:24:00+07:00 

coverimage: blog-cover.jpg

excerpt: "Incorporated provides a great typography, responsive design, author details, semantic markup and more."

authorname: Nicholas Whittier
authorlink: http://imperialwicket.com
authortwitter: nw_iw
authorgithub: imperialwicket 
authorbio: Some dude.
authorimage: faces.jpg
{{% /highlight %}}

#### Configurable & Code Snipped Highlighting

Highlighting requires [pygments](http://pygments.org), and to use the hugo-incorporated highlight style, `pygmentsuseclasses: true` must be in your site config.

/assets/stylesheets/main.scss:
{{% highlight scss %}}

/* Bodytext font */
$font: "Droid Sans", "Helvetica Neue", Helvetica, Arial, sans-serif;

/* Font for headings */
$fontheadings: "Droid Sans", "Helvetica Neue", Helvetica, Arial, sans-serif;

/* Text colors */
$text: #21272d;
$textmuted: #848484;
$accent: #2077b2;    
{{% /highlight %}}

config.yml:
{{% highlight yaml %}}
baseurl:            http://blog.nilproductions.com/
pygmentsuseclasses: true

params:
  inc:
    # Blog Information
    title:        "Hugo Incorporated"
    subtitle:     "Modern Hugo based blog for companies"
    cover_image:  blog-cover.jpg
    logo:         logo.png

    # Company information
    company:      nil productions
    url:          http://nilproductions.com/
#    facebook:     
    github:       nilproductions
    twitter:      nw_iw
#    gplus:        ''
    about_link:   http://nilproductions.com/about/

    # Product Information
    product_link: http://nilproductions.com/
    tagline:      "Coming up nil for quite some time."

    # Comments
    disqus:
      # Eg. "exampleblog" Set to false to disable comments
      shortname:  false

    # Sharing settings
    sharing:
      twitter:    false
      facebook:   false
      gplus:      false
      hn:         false

    # Analytics     
    analytics:
      google: false # Add tracking code in _includes/_google-analytics.html

    # Google Fonts
    # eg. 'Droid+Sans:400,700|Droid+Serif:400,700'
    google_font: 'Droid+Sans:400,700'
{{% /highlight %}}

**Zoomable images**
<div class="full zoomable"><img src="/images/incorporated.jpg"></div>

**Awesome quotes**
{{% quote %}}
“Effective companies tend to communicate more, their people are curious and they have opinions”
{{% /quote %}}

Stay tuned for updates.
