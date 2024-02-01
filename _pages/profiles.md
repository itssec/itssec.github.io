---
layout: profiles
permalink: /people/  # 指向的二级目录
title: People  # 显示的文字
description: Members of the itssec group.
nav: true
nav_order: 2

profiles:
  # 个人画像内容，如果包含多个人，则在下面添加多个block，并在_pages/中为每个概要文件创建一个内容文件。
  # if you want to include more than one profile, just replicate the following block
  # and create one content file for each profile inside _pages/
  - align: right
    # image: prof_pic.jpg
    content: about_einstein.md  # 人物简介对应的的md文件
    image_circular: false # 裁剪图像，使其成为圆形
    more_info: >
      <p>555 your office number</p>
      <p>123 your address street</p>
      <p>Your City, State 12345</p>
  - align: left
    # image: prof_pic.jpg
    content: about_einstein.md
    image_circular: false # crops the image to make it circular
    more_info: >
      <p>555 your office number</p>
      <p>123 your address street</p>
      <p>Your City, State 12345</p>
---
