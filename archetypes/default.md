---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
description: "This is a catchy short headline."
draft: false
toc: false
author: Joseph Fleet
slug: {{ replace .Name "-" " " | title }}
type: "post"
tags:
- Software
- Operating Systems
- Code
- Linux
image: "images/foo.bar"
---