<p align="center">
  <img src="banner.png" alt="AsylumRP" width="100%">
</p>

<h1 align="center">AsylumRP</h1>

<p align="center">
  <b>Custom Discord status for the Anime Asylum community</b><br>
  Show off what you're doing with your own text, pictures, links, timers and buttons.
</p>

<p align="center">
  <a href="../../releases/latest"><b>⬇️ Download</b></a>
  &nbsp;•&nbsp;
  <a href="https://discord.gg/anime-asylum"><b>💬 Join Anime Asylum</b></a>
  &nbsp;•&nbsp;
  <a href="TERMS.md"><b>📜 Terms of Service</b></a>
</p>

---

## ✨ Features

- 🎮 **Custom status:** show "Playing", "Watching", "Listening to" or "Competing in" with your own words
- 👀 **Live preview:** see exactly how your status looks before you send it
- 🔗 **Clickable text:** turn your Details and State lines into links (a GIF, a site, a server invite, anything)
- 🖼️ **Pictures:** large and small images with hover text and their own click links
- 🔁 **Rotating statuses:** cycle through as many statuses as you want, automatically
- 🧩 **Live variables:** `{app}`, `{time}`, `{cpu}`, `{ram}`, `{battery}`, `{random:a|b|c}` and more fill in by themselves
- 💤 **AFK mode:** switches to an away status when you leave your PC
- ⏱️ **Timers:** count up from a date, count down to a date, show local time and more
- 👥 **Party size:** show "(2 of 4)", up to 1500
- 🔘 **Buttons:** up to two link buttons on your profile
- 💾 **Profiles & templates:** save setups, switch between them and share them with friends
- 🎨 **Themes:** Asylum (neon), Dark and Light
- 🖥️ **Runs quietly:** minimizes to the tray, reconnects automatically and can start with Windows

---

## ⬇️ Download & install

1. Go to **[Releases](../../releases/latest)** and download the **AsylumRP** zip.
2. Right-click the zip → **Extract All…** and pick where to keep it.
3. Open the **AsylumRP** folder. Inside you'll see:
   ```
   AsylumRP/
   ├── AsylumRP.exe     ← double-click this to start
   ├── _internal/       ← needed to run, don't move or delete it
   └── How to use AsylumRP.txt   ← the full guide
   ```
4. Double-click **AsylumRP.exe**.

> ⚠️ **Keep `AsylumRP.exe` and `_internal` in the same folder.** If you want it on your desktop, make a shortcut instead of moving the exe: right-click `AsylumRP.exe` → **Send to → Desktop (create shortcut)**.

**You need:** Windows 10 or 11, and the **Discord desktop app** (the browser version of Discord can't show custom statuses).

### "Windows protected your PC"?
AsylumRP is new, so Windows may warn you the first time. Click **More info → Run anyway**.
This is a common false alarm for new programs that aren't signed with a paid certificate.

---

## 🚀 Setup (5 minutes)

**1. Make a Discord application**
- Go to the **[Discord Developer Portal](https://discord.com/developers/applications)** and log in.
- Click **New Application**, give it a name and click **Create**.
- The name you choose is what shows after **"Playing"** on your profile (for example *Anime Asylum*).

**2. Copy the Application ID**
- On the **General Information** page, click **Copy** under **Application ID**.

**3. Set your status**
- Open AsylumRP and paste the ID into **Application ID**.
- Type your **Details** (line 1) and **State** (line 2).
- Check the **Live Preview** on the right.

**4. Connect**
- Make sure the Discord desktop app is open, then click **Connect**.
- The badge at the top says **● LIVE ON DISCORD** when it's working. 🎉

> 💡 **Not showing?** In Discord go to **User Settings → Activity Privacy** and turn on **Share your detected activities with others**.

For the full guide, open **How to use AsylumRP.txt** in your AsylumRP folder (or **Help → Open User Guide** inside the app).

---

## 🖼️ Adding pictures

1. In the Developer Portal, open your application → **Rich Presence → Art Assets**.
2. Upload an image (at least 512×512) and give it a name, like `my_picture`.
3. Type that name into **Large image** or **Small image** in AsylumRP.

You can also paste any image link starting with `https://` instead. New uploads can take a few minutes to work.

---

## 🔗 Clickable text

Put a link in the **URL** box next to **Details** or **State**. When someone clicks those words on your profile, the link opens.

Example: Details `Activity Status` + URL `https://site.com/my-gif.gif` → clicking **Activity Status** opens your GIF.

---

## ⌨️ Shortcuts

| Keys | Action |
|---|---|
| **F5** | Connect |
| **Ctrl + Enter** | Update now |
| **Ctrl + S** | Save profile |
| **Ctrl + N** | New profile |
| **F1** | Getting Started |
| **Ctrl + Q** | Quit |

---

## ❓ Troubleshooting

| Problem | Fix |
|---|---|
| **"Couldn't reach Discord"** | Open the Discord **desktop app** and try again |
| **Nothing shows on my profile** | Turn on **Activity Privacy → Share your detected activities**, and wait up to 15 seconds |
| **"Invalid Client ID"** | Re-copy the **Application ID** from the Developer Portal |
| **Picture doesn't show** | Wait a few minutes after uploading, and check the name matches exactly |
| **I can't see my buttons** | Normal. Discord hides your own buttons from you; others can see them |
| **Program won't open** | Make sure `_internal` is in the same folder as `AsylumRP.exe` |

Still stuck? Ask in **[Anime Asylum](https://discord.gg/anime-asylum)**.

---

## 💾 Your settings

Everything you save is stored only on your computer:
```
C:\Users\<your name>\.asylumrp\profiles.json
```
Open it with **File → Open Settings Folder** inside AsylumRP.

**To uninstall:** turn off **Settings → Run When Windows Starts** (if it's on), quit AsylumRP, delete the AsylumRP folder, and optionally delete the `.asylumrp` folder above.

---

## 📜 Terms

By downloading or using AsylumRP you agree to the **[Terms of Service](TERMS.md)**.
AsylumRP is a fan-made tool and is **not affiliated with or endorsed by Discord Inc.**

<p align="center">
  Made with 💜 by <b>selfcentereddouchebag</b> for <b>Anime Asylum</b><br>
  <a href="https://discord.gg/anime-asylum">discord.gg/anime-asylum</a>
</p>
