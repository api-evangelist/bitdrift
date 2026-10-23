---
title: "Reducing Android JVM allocations for less memory pressure and faster logs"
url: "https://blog.bitdrift.io/post/reducing-android-jvm-allocations"
date: "2026-07-02"
author: "Fran Aguilera"
feed_url: "https://blog.bitdrift.io/feed.xml"
---
Substantially reduce JVM allocations on common Android logging paths by removing map-shaped work from SDK internals and improve runtime along the way.
