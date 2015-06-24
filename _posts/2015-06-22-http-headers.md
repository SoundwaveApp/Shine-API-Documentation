---
layout: page
title: "Response Headers"
category: ref
date: 2015-06-22 15:58:53
---

The API will return certain headers to indicate rate limit status on a per-API-key basis, as well as to indicate the time at which the resource was last cached.

* `X-RateLimit-Limit` - the current rate limit for this API key
* `X-RateLimit-Used` - the number of method calls used on this API key this minute
* `X-RateLimit-Remaining` - the estimated number of remaining calls allowed by this API key this minute
* `X-Last-Cached` - when this resource was last cached (ISO 8601 Timestamp)

