# Stemify

Drag a song on your Mac and a ring pops up. Drop it on a part and Stemify pulls that part out of the song, saved right next to the original as `Song (Vocals).mp3`.

**Parts:** Vocals · Instrumental · Bass · Drums · Guitar · Melodics

Everything runs on your Mac. No internet, no uploads.

Stemify is in private beta. Thanks for testing it!

## Requirements

- A Mac with **Apple Silicon** (M1 or newer). Apple menu → About This Mac should say **Apple M…**. Intel Macs aren't supported.
- About 1 GB of free space for the app.

## Install

1. Open **[Releases](../../releases)** and download the latest `Stemify-…-arm64.dmg`.
2. Open the `.dmg` and drag **Stemify** into **Applications**.
3. Open Stemify. macOS will say it can't verify the app, because it isn't signed with an Apple Developer account yet. Click **Done**, then go to **System Settings → Privacy & Security**, scroll down, and click **Open Anyway** next to Stemify.
4. A music note icon appears in your menu bar. Drag a song to try it.

If macOS says the app is "damaged", open Terminal and run `xattr -cr /Applications/Stemify.app`, then open it again.

## Get notified about new versions

On this page, click **Watch → Custom → Releases → Apply**. GitHub will email you whenever a new version is out.

## Using it

- Works with **MP3, WAV, M4A, AAC, FLAC and AIFF**.
- The first part of a song takes about 20–40 seconds. Stemify keeps working in the background and notifies you when it's saved.
- Other parts of the **same song** are then almost instant, because Stemify remembers recent songs.
- Drop in the middle of the ring to cancel. Click the middle while it's working to stop.
- **⌃⌥S** turns Stemify on or off. Change it in **Settings** (menu bar icon → Settings…), along with the output format (same as the song, WAV or MP3) and opening at login.

## Found a bug or have an idea?

Open an **[Issue](../../issues)**, or message Kunal, and say which song format you used, which part you picked, and what happened.

---

Stemify uses [Demucs](https://github.com/facebookresearch/demucs) by Meta (MIT License) for separation.
