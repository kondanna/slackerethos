---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
tags: ["first"]
author: "Kosi"
description: "Desc Text."
canonicalURL: "https://canonical.url/to/page"
disableHLJS: true
summary: "Sample summary"
description: "Sample description"
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
cover:
    image: "<image path/url>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
params:
  ShowPostNavLinks: true
---

