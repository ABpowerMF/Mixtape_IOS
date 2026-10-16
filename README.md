# Mixtape for iPhone

A music player for the songs on your phone. Import your Spotify playlists, and Mixtape finds those songs in your music (and can download the ones you don't have). No account, no ads, no Premium.

Mixtape isn't on the App Store, so you install it yourself from a computer with a free tool called **Sideloadly**. It takes about 10 minutes the first time.

---

## What you need

- An iPhone on **iOS 16 or newer**
- A **Windows PC or Mac**
- A **USB cable** for your iPhone
- An **Apple ID** (the one you already use is fine)

---

## 1. Download Mixtape

Go to the **Releases** page of this repo (on the right side of the page) and download the newest `Mixtape-iOS-vX.X.ipa` file.

## 2. Install Sideloadly on your computer

**Windows:**
1. Install **iTunes** and **iCloud** from Apple's website, **not** from the Microsoft Store (Sideloadly doesn't work with the Store versions):
   - iTunes: https://www.apple.com/itunes/download/win64
   - iCloud: https://support.apple.com/en-us/103232
2. Download and install **Sideloadly**: https://sideloadly.io

**Mac:**
1. Download and install **Sideloadly**: https://sideloadly.io

## 3. Put Mixtape on your iPhone

1. Plug your iPhone into the computer. On the iPhone, tap **Trust** and enter your passcode.
2. Open **Sideloadly**. Your iPhone shows up at the top.
3. Drag the `.ipa` file into Sideloadly (or click the IPA icon and pick it).
4. Type your **Apple ID** email in the Apple account box.
5. Click **Start**. Enter your Apple ID password, and the 2-factor code if Apple asks for one.
6. Wait until it says **Done**.

> Your password only goes to Apple, to sign the app for your phone. If you'd rather not use your main Apple ID, you can make a second free one just for this.

## 4. Allow it on your iPhone

The first time, iOS blocks apps you install yourself. You only do this once.

1. **Turn on Developer Mode**
   Settings › Privacy & Security › **Developer Mode** › On. The iPhone restarts. After it restarts, tap **Turn On** and enter your passcode.
   *(If you don't see Developer Mode, install the app first (step 3), then look again.)*
2. **Trust your Apple ID**
   Settings › General › **VPN & Device Management** › tap your Apple ID › **Trust**.
3. Open **Mixtape**. 🎶

---

## The 7-day thing (important)

With a free Apple ID, Apple only lets apps you install yourself run for **7 days**. After that, Mixtape won't open until you re-install it.

**Your music and playlists are NOT deleted.** Just repeat step 3 (plug in, drag the .ipa, Start) and everything is still there.

To skip doing it by hand, turn on Sideloadly's **automatic refresh**: before clicking Start, open **Advanced options** and tick **Automatic Refresh**. Then, while your computer is on and the iPhone is on the same Wi-Fi, Sideloadly refreshes Mixtape by itself before the 7 days run out.

*(A paid Apple Developer account, about $99/year, makes it last a full year instead.)*

## Updating to a new version

Download the new `.ipa` from Releases and install it the same way (step 3). It replaces the old version and keeps your music, playlists and settings.

---

## Getting your music in

- **Import files:** in Mixtape tap **import files** (Songs tab or Settings) and pick songs or a whole folder from iCloud Drive, a USB stick, etc.
- **Files app:** open the Files app › On My iPhone › **Mixtape** › Music, and drop songs in there. They show up in Mixtape automatically.
- **AirDrop / "Open in":** send a song to your iPhone and choose **Mixtape**.
- **Spotify playlists:** Playlists tab › **import from spotify** › paste the playlist link (Spotify › ••• › Share › Copy link). The playlist has to be public.
- **Downloads:** in the Download tab, type a song or paste a YouTube / Spotify link. For an imported playlist, tap **download missing** to get the songs you don't have.

Tip: downloads keep going while music is playing. If nothing is playing, keep Mixtape open until they finish (iPhones pause apps in the background).

---

## Problems?

| What happens | What to do |
|---|---|
| Sideloadly doesn't see my iPhone | Unlock the iPhone, tap **Trust**, try another cable/USB port. On Windows, make sure iTunes is the apple.com version. |
| "Untrusted Developer" when opening Mixtape | Do step 4.2 (VPN & Device Management › Trust). |
| "Developer Mode required" | Do step 4.1, and let the iPhone restart. |
| Mixtape suddenly won't open | The 7 days ran out. Re-install it (step 3). Nothing is lost. |
| "Maximum App ID limit reached" / "3 apps" error | Free Apple IDs can only have 3 self-installed apps at once. Delete one you don't use, or wait a few days. |
| Sideloadly asks for a password again and again | Make sure the 2-factor code is entered, or try an app-specific password from appleid.apple.com. |
| A song won't download | Try again, or pick a different result. YouTube sometimes blocks a video. |
| Spotify import fails | Check the playlist is **public** and the link is a playlist/album/song link. |

---

*Mixtape is a personal project, not affiliated with Spotify, YouTube or Apple. Lyrics come from LRCLIB.*
