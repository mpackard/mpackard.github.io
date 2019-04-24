---
id: 300
title: disable web access from a mac
date: 2011-03-17T14:57:59+00:00
author: mpackard
layout: post
guid: http://aquamap.net/blog/?p=300
permalink: /?p=300
categories:
  - Uncategorized
---
From http://discussions.apple.com/thread.jspa?threadID=2016206

The question was &#8220;How do you temporarily disable web access on a mac?&#8221;. The answer was:

ipfw add 2005 deny tcp from any to any 80 out xmit en0

Replace en0 with whatever network interface is active. Someone else asked how to undo it. I would have responded but the thread is closed. Here is what i would have said:

ipfw delete 2005