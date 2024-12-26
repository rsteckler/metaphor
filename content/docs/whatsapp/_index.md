---
title: WhatsApp API
weight: 4
type: docs
prev: docs/foundation
next: docs/middleware
sidebar:
  open: true
---

Ideally, we would create a WhatsApp bot to manage the messages, but Meta requires a Facebook Business account in order to access the WhatsApp APIs.  When I tried to create one, it was flagged as suspicious within 15 seconds of creation despite having decades of Facebook history and multiple deployed apps with no issues.  When I tried to veirfy my identity the Facebook page sent a server error, which leads us to the excellent [whatsapp-api](https://github.com/chrishubert/whatsapp-api/) from Chris Hubert.  

1. Run the docker container
2. Make sure ping works
3. Switch to bot account on WhatsApp
4. Link bot account