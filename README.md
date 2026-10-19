# ShareSign for Claude

Prepare contracts for e-signature, find evidence in virtual data rooms, and review signing progress in the same conversation. ShareSign combines electronic signatures and secure data rooms for founders, advisers and teams.

## Tasks

- **Prepare an agreement:** “Prepare an offer-letter draft from my template for my review.” Ask only for missing recipient details and essential terms, then return an unsent draft and readiness checklist.
- **Research a room:** “Find the change-of-control clause in our due-diligence room and cite the pages.” Identify the evidence and disclose files that could not be searched.
- **Business brief:** “What is awaiting signature, and what needs attention?” Separate drafts, sent agreements and completed documents, with source links.
- **Organise a completed agreement:** “Help me choose a room for this signed agreement.” Suggest an authorised room/folder and open ShareSign for deliberate private-copy confirmation. Nothing is copied from the chat alone.
- **Viewer activity:** “Who has opened the pitch deck?” Requires its own approved permission; observed activity does not establish investor intent.

## Connection

The bundle includes five skills and one remote production MCP server at https://sharesign.co/mcp. It runs no local server, hooks or executables and contains no credentials. Start with **Get started**. For a chat-only brief, supply the text or agreed terms without connecting. For connected tasks, use the host's actual sign-in flow, then select your business and permissions in ShareSign. A fresh context read confirms that connection. Do not paste passwords or codes into chat.

Connected ShareSign workflows require Pro or Business, including active qualifying partner offers. A brief from supplied terms needs no ShareSign account and creates no ShareSign record. Other founders can use normal setup at https://sharesign.co and optional fictional examples at https://sharesign.co/examples. No fundraising onboarding is required.

Read-only consent remains useful. Preparing drafts, searching file contents and individual viewer activity each require additional permission. This bundle does not send or sign agreements, publish or invite to rooms, automatically file signed copies, issue shares, calculate valuations or change your billing. Review, send and complete your own signatures in ShareSign. To return to an unfinished signature, open its agreement record and choose Continue signing when it is your turn. Signing on your behalf is unsupported, rather than an extra permission you can grant.

## Privacy and recovery

Choose the business and access deliberately. Document search can return excerpts; analytics can return individual viewer activity. Information received by Claude is also subject to your Anthropic settings. Revoking ShareSign access blocks future retrieval; it does not remove previous conversation content. Installation or upgrade does not expand an existing grant.

If newly released tools are missing, use the supported Refresh tools list control in Claude, then start a new conversation. If tools are unavailable, distinguish incomplete dependency loading from login failure. Use the host's actual connection controls and the [connection guide](https://sharesign.co/docs/connect#agents). Duplicate custom connectors must not be mixed with this plugin. Do not remove your existing connector until the intended production connection has been verified.

A saved unsent draft survives an interrupted conversation. Retry the same operation with the same idempotency key and inputs. A changed recipient needs a fresh version and deliberate edit. In a new conversation, read fresh connection context and inspect your template or PDF preparation operation, or list your actor-owned operations if its identity was lost. Saved recovery returns the current document and preserves human edits. A saved PDF result survives temporary upload expiry. PDF creation still requires real supported file transfer; a chat attachment alone is not an uploaded file.

## Public installation and verification

ShareSign is listed for Claude apps, Cowork and Claude Code. Add the public plugin from https://claude.ai/customize/plugins/id/2e74e5f1-bfc2-42b1-886e-636b524650d3%40anthropic-plugin-directory.

For Claude Code, use the official directory source:

```sh
claude plugin install sharesign@anthropic-plugin-directory --scope local
```

That command installs the version currently served by the directory, not necessarily the version of this source tree. The published 0.1.5 package has public-source Code, Claude web and macOS desktop/Cowork workflow evidence. The directory groups web, desktop and mobile as one target; Claude mobile has not been separately verified. A later package must pass its own checks and review before it is served. A local candidate, scan pass or source push alone does not establish public availability.

## Support

[Support](https://sharesign.co/support) · [Privacy](https://sharesign.co/legal/privacy) · [Terms](https://sharesign.co/legal/terms) · [Connection guide](https://sharesign.co/docs/connect#agents)

## Licence

Proprietary. Installation and use are permitted under the included LICENSE; other rights are reserved.

## Signing brief without a connection

This mode requires plugin 0.1.6 or later. The official directory can continue serving 0.1.5 until the newer version passes review and is published. Check the installed version; a source update alone does not add this mode to an older installation.

Ask Prepare agreement for a signing brief from text or agreed terms you supply in Claude. It reports stated facts, blanks and contradictions in chat. It neither reads nor saves ShareSign records and needs no ShareSign account. Connected preparation, research and progress workflows still require eligible ShareSign access and deliberate consent.
