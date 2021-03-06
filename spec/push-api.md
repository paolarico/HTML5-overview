---
layout:   page
category: spec
title:    "Push API"
---

| Current Status | Working Draft (WD)
| Canonical URI | [`http://www.w3.org/TR/push-api`](http://www.w3.org/TR/push-api)
| Abstract | The Push API enables sending of a push message to a webapp via a push service. An application server can send a push message at any time, even when a webapp or user agent is inactive. The push service ensures reliable and efficient delivery to the user agent. Push messages are delivered to a Service Worker that runs in the origin of the webapp, which can use the information in the message to update local state or display a notification to the user. This specification is designed for use with the web push protocol, which describes how an application server or user agent interacts with a push service.