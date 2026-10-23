---
title: "Announcing workflow debugging"
url: "https://blog.bitdrift.io/post/announcing-workflow-debugger"
date: "2025-10-20"
author: "Matt Klein"
feed_url: "https://blog.bitdrift.io/feed.xml"
---
bitdrift Capture just got even more powerful: as of today, we’ve added workflow debugging! As we have worked with more and more customers, it has become extremely clear that one of the biggest side-effects of workflows being so flexible and powerful is the complexity of understanding whether a workflow state machine is going to properly match client-side events when it is deployed. Is there no data because there is actually no data or is there no data because one of the match conditions is incorrect when applied to device logs?
