---
title: Sequence diagram authentication
date: 2024-01-16 11:00:00 +07:00
categories: [Authentication, spring]
tags: [spring ]     # TAG names should always be lowercase
---
This is a guide how to you can do authentication login. You login and request a token jwt -> server generated jwt token with two parts. 
Payload + header and secret key. So then server verify token if this is exactly signKey from user and server will return result also accept user's login.
![hinh-anh](/assets/img/authen.png) 

You can remember what authentication do under the hook ! Exactly

