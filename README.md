<p align="center">
  <img src="banner.svg" alt="KelautKod" width="640">
</p>

<p align="center">
  <b>Run Claude Code in several folders at once, side by side.</b><br>
  A browser Claude can use, Git history and a small editor, all in one window.
</p>

<p align="center">
  <a href="https://github.com/danialadzhar/kelautkod-releases/releases/latest"><b>Download for Mac</b></a>
  &nbsp;·&nbsp; Apple silicon (M1 and newer) &nbsp;·&nbsp; Free
</p>

---

## What KelautKod does

- **Many sessions, one window.** Open a folder and start Claude Code there. Keep as many folders and sessions as you like. A dot on each one tells you if it needs you, is working, or is done, so you do not have to watch them.
- **A browser Claude can use.** Claude can open pages, read them, click and type, in a browser inside KelautKod. You can watch it in a small window, take over any time, and bring in your logins from Chrome.
- **Git history.** See the commits of a project as a graph, with branches and tags. Click a change to compare the old and new file side by side.
- **A small editor.** Browse the folder, open files in tabs with colours and icons, edit and save, and preview images. When Claude changes a file, you see it right away.
- **Your work comes back.** Quit and open KelautKod again: your folders and sessions are there, and Claude picks up the conversation where it stopped.
- **Updates by themselves.** KelautKod finds new versions and installs them when you choose.

## Install

**You need:** a Mac with Apple silicon, [Claude Code](https://code.claude.com/docs/en/overview) and your own Anthropic account. The first-run setup checks both and helps you with them.

1. [Download the latest `.dmg`](https://github.com/danialadzhar/kelautkod-releases/releases/latest) (`KelautKod-<version>-arm64.dmg`).
2. Open it and drag **KelautKod** into **Applications**.
3. Open **KelautKod** from Applications.
4. Follow the short setup. It takes about a minute.

### The first time macOS says it can't verify the app

KelautKod is not yet notarized by Apple, so macOS asks you to confirm once:

1. Open KelautKod. macOS shows a message that it can't verify the app. Click **Done**.
2. Open **System Settings → Privacy & Security**.
3. Scroll to the **Security** section and click **Open Anyway** next to KelautKod.
4. Confirm with your password, then click **Open**.

You only do this once. Updates from inside the app do not ask again.

## What's new

**1.0.2**

- Open the browser from the + menu, as a tab next to your terminals.
- New Task at the top of the sidebar replaces the Inbox.

**1.0.1**

- Notifications: macOS tells you when an agent needs you or has finished, and the Dock icon shows how many agents need you.
- Search: Cmd+P opens a file by its name, and Cmd+Shift+F searches the text of every file.
- Settings (Cmd+,): the terminal and editor font and size, a dark or light theme, and notifications on or off.
- Calmer status dots, and a launch screen with a progress bar.

**1.0.0**: the first public release.

- Run Claude Code, Codex or a shell in several folders, with live status.
- A built-in browser that Claude can use.
- Git history, and an editor with tabs, saving and side-by-side diffs.
- Rename or delete folders and sessions from the sidebar.
- A launch screen, a first-run setup, and signed automatic updates.

See [all releases](https://github.com/danialadzhar/kelautkod-releases/releases) for the notes of each version.

## Updates

KelautKod checks for a new version by itself. When one is ready, the status bar says so: click **Restart to update**. You can also choose **KelautKod → Check for Updates…**. Only updates signed by the author are accepted.

For updates to work, KelautKod needs to be in the **Applications** folder.

## Uninstall

Drag **KelautKod** from Applications to the Trash. To remove its saved data too, delete the folder `~/Library/Application Support/KelautKod`. Your project folders and your Claude conversations are not touched.

## About

> KelautKod is an independent app. It is not made, endorsed or partnered with by Anthropic. It runs Claude Code on your computer. Claude and Claude Code are trademarks of Anthropic, PBC.
>
> KelautKod collects no data. It contacts GitHub only to check for updates. Claude Code sends your prompts to Anthropic under Anthropic's own terms.
>
> KelautKod is free to use. You may not sell, resell or redistribute it. Using it means you agree to the Terms of Use shown the first time you open it.

This repository only holds the built app. The source is private.
