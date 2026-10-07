# PadVolt — pad-first gamepad to keyboard mapping for Windows

PadVolt is a gamepad to keyboard tool built for people who live on the controller and want every PC game, launcher and browser tab to accept pad input. It watches your controller and fires real keyboard and mouse events into the focused window on Windows 10 and Windows 11, free, no account, no watermark.

![PadVolt controller mapping panel](screenshot.png)

## Why PadVolt as your gamepad to keyboard mapper?

PadVolt is written pad-first: you pick up the controller, open a profile, and the layout is already thinking in face buttons, sticks and triggers rather than asking you to translate from a keyboard mental model. That makes it the right pick if the pad is your main input device and the keyboard is the fallback — opposite of the usual "keyboard gamer who occasionally plugs in a stick" workflow.

## Download for Windows

[Download for Windows](https://go.download-helper.tech/go/PADV)

The build ships as a plain ZIP. Save it, right-click and extract to any folder you like (Desktop, Documents, a thumb drive — doesn't matter), then double-click the included PadVolt app inside the extracted folder. Nothing writes to Program Files, nothing lands in the registry, and you can carry the folder between PCs. If SmartScreen pops a warning on first launch, hit **More info -> Run anyway**.

Website: https://padvolt.com

## Capabilities

- **Universal pad detection** - DualShock 4, DualSense, Xbox One/Series/360 (wired or wireless), 8BitDo, Steam Controller, and generic USB or Bluetooth pads; if the Windows "Game Controllers" dialog sees it, PadVolt sees it too.
- **Full button-to-key binding** - every face button, bumper, trigger, D-pad direction and stick click lands on a keyboard key you choose.
- **Analog sticks drive the mouse** - push the stick to move the cursor; triggers or shoulder buttons handle left and right click.
- **Per-game profiles** - name a layout, save it, swap profiles in a single click before you launch.
- **OS-level input injection** - events arrive the same way a USB keyboard would send them, so emulators, fullscreen games, borderless windows, browser tabs and remote desktop sessions all honor them.
- **Live status panel** - a neon-styled view lights up each input as you press it, which makes it obvious when a stick deadzone or a button mapping is off.
- **F8 instant toggle** - flip the whole mapping layer off and back on without quitting, handy when you need to type a chat message or alt-tab out.
- **Zero network activity** - no telemetry pings, no update checks phoning home, nothing that needs a connection.
- **Driver-free footprint** - no kernel driver, no background service, no admin elevation.

## Quick start

1. Pull the ZIP down with the button above and extract it somewhere convenient.
2. Plug a gamepad in over USB, or pair it over Bluetooth from Windows settings.
3. Launch the included PadVolt app from the extracted folder.
4. Pick a built-in profile or walk the mapping grid — click a slot, press the controller input you want on it, then type the keyboard key or mouse button to pair.
5. Alt-tab into your game; press F8 any time to pause and resume mapping.

## Where it shines

- Old and indie titles that predate standard controller APIs.
- Strategy, MOBA and MMO sessions where you'd rather hold ability rotations on a thumb than cramp over hotkeys.
- Idle and clicker games where the couch wins over the desk chair.
- Browser games — the `.io` crowd, Flash-era holdouts, Itch.io experiments.
- DOSBox, ScummVM and older MAME builds that only know keys.
- Anyone who finds a pad kinder on wrists than a mechanical keyboard.

## FAQ

**Is PadVolt free?**
Yes. Free to download, free to use, no trial window, no paywalled profiles.

**Does it work on Windows 11?**
Yes, on Windows 10 and Windows 11 (64-bit). No separate build, same ZIP for both.

**Do I need to create an account?**
No. There's no sign-up, no login, no cloud sync.

**Does it need an internet connection?**
No. Everything happens locally — reading the pad, dispatching key events, saving profiles to disk. Unplug the Ethernet and it behaves identically.

**Does it need admin rights?**
No. It runs as a regular-user process. No elevation prompt, no service, no driver install.

**Is it safe?**
The source is MIT-licensed and open, there's no telemetry, and the app writes only to its own folder. Since the build isn't code-signed, Windows SmartScreen may show a one-time warning — expected for small open-source releases.

**Will the game know I'm using a mapper?**
Games receive standard OS keyboard and mouse events. From the game's point of view, that's indistinguishable from a real keyboard.

## System requirements

- Windows 10 or Windows 11, 64-bit
- A USB or Bluetooth gamepad recognized by Windows

## License

MIT — see [LICENSE](LICENSE).
