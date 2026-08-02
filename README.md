# Hey, I'm Starkka 👋

I build and port software for devices the industry gave up on.

## Keeping old systems alive

Most of my work targets platforms that stopped getting official support years ago: the HP TouchPad (webOS, 2011), Windows 10 Mobile Lumias, Windows Mobile PDAs, and other "dead" hardware that still works perfectly fine. These devices aren't e-waste — they're capable machines that just need someone willing to write software for them.

That means porting modern engines to old OSes (a current WebKit on a 2015 Lumia), writing new clients for modern services (Nextcloud, KDE Connect, Navidrome on platforms that never had them), and building the tooling to make development on these systems possible at all.

If a device still powers on, it deserves software.

## Why everything here is source-available

Old-platform development only survives through shared source. Every dead platform's homebrew scene runs on the code people published before they moved on — and dies a little every time a maintainer takes their work closed or disappears with it. SDKs vanish, download servers go dark, and the only thing that keeps a 15-year-old device usable is that somebody, somewhere, kept the source public.

So my originals are open, my ports respect and keep their upstream licenses, and my forks credit the people who did the foundation work. If I get hit by a bus, everything I've built stays buildable.

## How I use AI

I develop with heavy AI assistance ([Claude Code](https://claude.com/claude-code)), and I'd rather say so plainly than pretend otherwise. What that means in practice:

- **A human directs the work.** I decide what gets built and make the architecture calls. The AI is a tool I drive, not an autopilot.
- **Nothing ships until it works on real hardware.** Code isn't done because it compiles — it's done when the feature runs on the actual device. I test on the real TouchPad, the real Lumia, the real Deck. A green build is not the finish line.
- **I read and own every change.** Bugs and design decisions here are mine, whatever wrote the code.
- **Licensing and credit are my responsibility.** I build from open source, respect upstream licenses, and don't use AI to launder anyone's work or strip attribution.

Most of my repos carry a full [AI disclosure](https://github.com/Starkka15) explaining this per-project, so you can make an informed call about using them.

## Featured projects

### 📱 [PocketTavern](https://github.com/Starkka15/PocketTavern)
The best source-available AI chat app for Android. SillyTavern-compatible — character cards, group chats, lorebooks — with on-device inference so your conversations can stay entirely on your phone. Also ported to [Windows 10 Mobile / UWP](https://github.com/Starkka15/PocketTavern.UWP), because a chat client is exactly the kind of app an old phone can still do well.

### 🎮 [GameVault](https://github.com/Starkka15/GameVault)
Multi-store game launcher for the Steam Deck — Epic, GOG, Amazon, itch.io, EA Play, and RPG Maker titles, installed and launched from Game Mode like native games. Community fork of Junk-Store, kept open and kept moving.

## The rest of the fleet

| Platform | Projects |
|---|---|
| **webOS (HP TouchPad)** | [Moonlight](https://github.com/Starkka15/moonlight-webos) · [Nextcloud](https://github.com/Starkka15/nextcloud-webos) · [OpenTTD](https://github.com/Starkka15/OpenTTD-WebOS-Port) · [Prism browser](https://github.com/Starkka15/prism-browser) · [comic reader](https://github.com/Starkka15/comic-reader-webos) · [Cockpit](https://github.com/Starkka15/cockpit-webos) · [SDL2 shim](https://github.com/Starkka15/sdl2-compat-webos) |
| **Windows 10 Mobile** | [Revenant](https://github.com/Starkka15/revenant-browser-w10m) (modern WebKit engine) · [Konnect](https://github.com/Starkka15/konnect-uwp) (KDE Connect) · [Nextcloud](https://github.com/Starkka15/nextcloud-uwp) · [NokiDrome](https://github.com/Starkka15/NokiDrome) · [Seeneva](https://github.com/Starkka15/Seeneva.UWP) |
| **Linux / Steam Deck** | [Optima](https://github.com/Starkka15/Optima) (Ubisoft client) · [Maxima](https://github.com/Starkka15/Maxima) (EA client) · [webOS PDK runner](https://github.com/Starkka15/webos-pdk-runner) (run ARM webOS games on x86) |

---

*If it still powers on, it deserves software.*
