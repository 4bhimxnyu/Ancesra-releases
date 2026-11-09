<p align="center">
  <img src="https://ancesra.vercel.app/assets/logo.png" width="96" height="96" alt="Ancesra AI logo">
</p>

<h1 align="center">Ancesra AI</h1>

<p align="center">
  <b>no signal. no cloud. no problem.</b><br>
  A free, private AI assistant that runs fully offline on your Windows PC.<br>
  <sub>Formerly called Nexus.</sub>
</p>

<p align="center">
  <a href="https://ancesra.vercel.app/download"><b>⬇ Download for Windows</b></a> ·
  <a href="https://ancesra.vercel.app">Website</a> ·
  <a href="https://ancesra.vercel.app/docs">Docs</a> ·
  <a href="https://github.com/4bhimxnyu/Nexus-releases/releases">All releases</a>
</p>

---

## What it does

- **Chat, Coding and Debug modes.** A direct answer first, then the key points. Coding mode gives the approach, the code and its complexity. Debug mode names the bug and returns the fixed code.
- **My files.** Add PDFs, Word documents and notes, and Ancesra answers from them, naming the file and page. Files are read on your computer and never uploaded.
- **Knows recent events.** A built-in Wikipedia pack covers 2024–2026, searched offline, with sources shown.
- **Memory you control.** Say "remember that…" and it asks before saving. See and delete everything on your Profile.
- **Updates itself** when you're online, and keeps working when you're not.

## Install (Windows 10/11, 64-bit)

1. **[Download the installer](https://ancesra.vercel.app/download)** (`Ancesra-Setup-<version>.exe`, about 120 MB). It's also in the **Assets** of the [latest release](https://github.com/4bhimxnyu/Nexus-releases/releases/latest).
2. Run it. Windows may say "Windows protected your PC" because the installer isn't code-signed yet: click **More info → Run anyway**.
3. Open Ancesra **with the internet on, once**. It sets itself up, with progress on screen:
   - installs [Ollama](https://ollama.com), the free program that runs the AI (about 1.7 GB, if it isn't already installed)
   - downloads the AI model phi4-mini (about 2.5 GB) and a small search model (0.3 GB)
4. Done. From then on Ancesra works with the internet off.

**Needs:** about 6 GB of free disk space and 8 GB of memory. A graphics card is optional (it makes answers faster).
macOS: coming later.

## Privacy

Your chats, files, profile and memory never leave your computer. There's no account and no analytics.
The only things that use the internet are the first setup (downloading Ollama and the models) and the update check, which asks GitHub for the latest version number.

## Upgrading from Nexus

Installed Nexus 2.4 or earlier? It offers the update by itself the next time it's online. After updating it opens as **Ancesra AI**, with your chats, profile, memory and files kept.

## Feedback

- Something broke or gave a wrong answer? [Report a bug](https://github.com/4bhimxnyu/Nexus-releases/issues/new?title=Bug:%20) with your app version (bottom of the sidebar).
- An idea? [Suggest it](https://github.com/4bhimxnyu/Nexus-releases/issues/new?title=Idea:%20).
- A security problem? Report it privately from this repository's **Security** tab.

## Licence

Ancesra AI is © 2026 Abhimanyu, licensed under the GNU AGPL-3.0. The AI model (phi4-mini, MIT), Ollama (MIT) and the other parts keep their own licences, listed in `THIRD-PARTY-LICENSES.md` inside the app.

This repository hosts the installers and release notes; the app checks it for updates, which is why it keeps its original name.
