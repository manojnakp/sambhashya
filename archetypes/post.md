---
title: "{{ replace .Name "-" " " | title }}" # Title of the blog post.
date: {{ .Date }} # Date of post creation.
description: "Article description." # Description used for search engine.
# keywords = ["blog", "hugo", "tech", "golang", "coding", "computer-science"] # meta tag (SEO) keywords here.
featured: true # Sets if post is a featured post, making it appear on the sidebar.
draft: true # Sets whether to render this page. Draft of true will not be rendered.
toc: true # Controls if a table of contents should be generated for first-level links automatically.
# menu: main
# usePageBundles: false # override page bundles
singleColumn: true
featureImage: "/images/path/file.jpg" # Sets featured image on blog post.
featureImageAlt: 'Description of image' # Alternative text for featured image.
featureImageCap: 'This is the featured image.' # Caption (optional).
thumbnail: "/images/path/thumbnail.png" # Sets thumbnail image appearing inside card on homepage. (req.)
shareImage: "/images/path/share.png" # Designate a separate image for social media sharing.
categories:
- Technology
tags:
- Tag_name1
- Tag_name2
---

**Insert Lead paragraph here.**
