# superbridge

**One group chat. Every app your people already use.**

Superbridge isn't a company or a product you sign up for. It's what a community's chat looks like once every platform it uses has been bridged together: Telegram, Discord, Signal, WhatsApp, and more, all landing in the same room.

Site: **[superbridge.chat](https://superbridge.chat)**

## How it works

A [Matrix](https://matrix.org) server is self-hosted. Each platform is then bridged in through a bot sitting in the chat, talking to [mautrix](https://docs.mau.fi/bridges/) running on that same Matrix server. Every message sent on any platform gets relayed out to all the others. Nobody has to leave the app they already have open.

## What can be bridged

Telegram, Discord, Signal, WhatsApp, Matrix, Slack, Messenger, Instagram, iMessage, Google Chat, Google Messages, Google Voice, LinkedIn, IRC, Bluesky, Zulip, and X. See the full, current list at [docs.mau.fi/bridges](https://docs.mau.fi/bridges/).

## Run it yourself, or have it run for you

- **Get it set up for you**: if you run a community, [Electron Network](https://electronworkshop.org/network/) handles the infrastructure. You just invite the bots.
- **Build it yourself**: mautrix is open source. Wire up your own bridges at [docs.mau.fi/bridges](https://docs.mau.fi/bridges/)

## Superbridged chats

Real communities already running as one room across every app. See the current list on [superbridge.chat](https://superbridge.chat).

## This repo

A single static page (`index.html`), no build step. Serve it with anything that serves static files, e.g.:

```
python3 -m http.server 8000
```

Credit: foundational discovery done by [Angie](https://www.linkedin.com/in/anjsimmo/) and [Nick](https://www.linkedin.com/in/nicholas-meinhold-3864b812/).
