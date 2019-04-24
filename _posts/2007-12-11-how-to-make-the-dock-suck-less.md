---
id: 156
title: how to make the dock suck less
date: 2007-12-11T14:15:00+00:00
author: mpackard
layout: post
#guid: http://aquamap.net/blog/?p=156
#permalink: /?p=156
categories:
  - Uncategorized
---
open a terminal:

defaults write com.apple.dock pinning end  
killall -c Dock

That keeps the trash can&#8211;the only thing in the dock I really use&#8211;in the lower right corner.

Update, Leopard version:

defaults write com.apple.dock no-glass -boolean YES
