---
title: "IBM MQ Little Gem #59: SERVICE object STATUS"
url: "https://community.ibm.com/community/user/blogs/morag-hughson/2026/06/14/ibm-mq-little-gem-59-service-object-status"
date: "2026-06-14"
author: "Morag Hughson"
feed_url: "https://community.ibm.com/community/user/integration/communities/community-home?CommunityKey=183ec850-4947-49c8-9a2e-8e7c7fc46c64"
---
This post explores how IBM MQ SERVICE objects track process information through the DISPLAY SVSTATUS command. When a program starts via START SERVICE, the queue manager remembers the PID of the started process, making it visible in status displays and usable in stop commands even if the application has not connected to the queue manager.
