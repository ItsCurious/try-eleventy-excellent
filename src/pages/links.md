---
title: Links
description: 'All link posts can be found here'
layout: blog
pagination:
  data: collections.linkPosts
  size: 5
permalink: 'links/{% if pagination.pageNumber >=1  %}page-{{ pagination.pageNumber + 1 }}/{% endif %}index.html'
---

This linklog has a pagination of **{{ pagination.size }}** posts per page.
The pagination is only shown if there are more posts ({{ collections.linkPosts.length }}) than items per page ({{ pagination.size }}).
