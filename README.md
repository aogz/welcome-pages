# Welcome Pages

Standalone start pages for the four Webfuse space types. Each page is a single self-contained HTML file (no build step), with the same 6-step tour skeleton, palette tuned to the space-type accent color from cobro's `space-types.ts`, and copy adapted to the use case.

- **Live:** https://aogz.github.io/welcome-pages/
- FontAwesome + Manrope loaded from CDNs.

## Pages

| File | Space type | Accent | Hero icon | Use case |
| --- | --- | --- | --- | --- |
| `meeting.html`    | Meeting    | `#3362d3` (current page palette) | `fa-hand`                  | Reusable URL for co-browsing with video, chat, and file sharing. |
| `assisted.html`   | Assisted   | `#F08030` orange                 | `fa-headphones`            | Pick up sessions from a queue and assist visitors in parallel. |
| `solo.html`       | Solo       | `#7F56D9` purple                 | `fa-wand-magic-sparkles`   | Single-participant browser to augment the web with apps & extensions. |
| `automation.html` | Automation | `#426FFF` blue                   | `fa-robot`                 | AI agent driving a real browser for forms, scraping, testing. |

## Tour skeleton (shared)

1. Top-left callout — type-specific (Participants / Visitors / Quick actions / Agent status)
2. Tabs — universal (`+` opens a new tab)
3. Top-right offset — type-specific (Video & Chat / Voice & chat / Web augmenters / Live logs)
4. Settings & Exit — universal
5. Make it your own — apps, extensions, space settings (examples vary by type)
6. Launch — drop in a URL to open in the space
