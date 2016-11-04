---
published: false
title: Proxy patching for nodejs
layout: post
tags: [javascript, nodejs]
---
1. original_proxy - construct with defineProperty
2. What if userHandler has trap for defineProperty
3. How to deal with get?
4. invariants for return value
5. setting variable outside scope in getter
6. invariants for configurable : true
7. but directly setting on target and thus polluting it
8. different approach of call forwarding
9. ownKeys issue
10. Array.isArray issue