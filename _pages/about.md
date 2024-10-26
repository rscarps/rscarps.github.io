---
permalink: /
title: "About this website"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is the front page of a technical writer portfolio website that is hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that technical writers have: portfolio, CV, publications. You can fork [this repository](https://github.com/rscarps/rscarps.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads.

A data-driven technical writer website
======
The content & metadata of this website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. These various markdown (.md), YAML (.yml), HTML, and CSS files are hosted in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/rscarps/rscarps.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/rscarps/rscarps.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/rscarps/rscarps.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://rscarps.github.io/talks), each [individual page](https://rscarps.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://rscarps.github.io/cv), and the [map of places you've given a talk](https://rscarps.github.io/talkmap.html) (if you run this [python file](https://github.com/rscarps/rscarps.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/rscarps/rscarps.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).
