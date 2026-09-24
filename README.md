<img src="assets/comethru.png" alt="comethru Apple app icon" width="128" height="128" />

# comethru for Gemini CLI

Create and run events in your comethru workspace through a conversation. Build event drafts, configure tickets and registration, review changes, and approve publication. Manage guests and event operations using the permissions you choose.

## Install

```sh
gemini extensions install https://github.com/The-Garber-Company/comethru-gemini-extension
```

Restart Gemini CLI, then authenticate:

```text
/mcp auth comethru
```

Sign in to comethru, choose your workspace and approve only the permissions you need. You need an organizer account, an eligible workspace plan and a role that permits the requested actions.

Try: “Help me create an event in comethru. Ask me what you need, one question at a time.”

## Review and control

Your assistant prepares changes for review before applying them. Publishing, messages, payments, refunds, deletion and access changes require specific approval. New events start with registration closed. Keep Gemini's tool confirmations enabled.

The server checks the current workspace membership, role and selected scopes. Revoke access in [Account → Connectors](https://www.comethru.app/dashboard/connectors). Revocation stops future access; it does not delete information already received by your assistant.

Guest-list access may share attendee names, contact details and ticket/check-in status with your assistant. Never paste passwords, payment-card details or pass credentials into a chat. Provider verification and some device tasks use secure browser/device screens.

## Support

- [comethru](https://www.comethru.app)
- [Setup and permissions](https://www.comethru.app/dashboard/connectors)
- [Privacy](https://www.comethru.app/privacy)
- [Terms](https://www.comethru.app/terms)
- support@comethru.events

This repository contains only the public Gemini CLI connector configuration, guidance and the comethru Apple app icon. The comethru service is hosted separately. Gemini CLI gallery inclusion depends on Google's indexing and validation; this package does not create a listing in the consumer Gemini app.

The comethru name and icon belong to The Garber Company. Their inclusion identifies this integration and does not grant a separate trademark license.
