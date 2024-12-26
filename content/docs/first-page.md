---
title: How It Works
weight: 1
type: docs
prev: /
next: docs/prerequisites/
---

1. Use your glasses to send a message to different whatsapp groups depending on what integration you want to trigger
2. Use whatsapp-api to listen for those messages and send them to a middleware (e.g. n8n, Zapier, IFTTT, or your own app)
3. Use that middleware to choose the correct action by parsing the WhatsApp group name and sending the message to the correct integration
4. Use the integration to process the content and perform an action or generate a response
5. If the response needs to be sent back to the glasses, use the response in the middleware to generate a WhatsApp message
6. Send that message back through whatsapp-api to the correct group message.  

> [!IMPORTANT]
> The second WhatsApp account is required if you want your glasses to read responses back to you.  Technically, you can just have the responses sent back via your own personal WhatsApp account, but since the message comes from you, the glasses won't read them out loud.




