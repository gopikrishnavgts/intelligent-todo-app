# Intelligent TODO for Mac

A to-do app and desktop widget for macOS, organized by **your own Claude Code**. Claude categorizes your to-dos, breaks them into subtasks, sets priorities and due dates, builds study plans, and tells you what to focus on now. Everything stays on your Mac.

## ⬇️ Download

**[Download IntelligentTODO.dmg](https://github.com/gopikrishnavgts/intelligent-todo-app/releases/latest/download/IntelligentTODO.dmg)**. This link always points to the latest version, and you don't need a GitHub account.

You can see all versions and what changed on the [Releases](https://github.com/gopikrishnavgts/intelligent-todo-app/releases) page.

## Install
1. Open the DMG and drag **Intelligent TODO** onto **Applications**.
2. **First launch only:** macOS blocks apps that aren't notarized. Open the app, click **Done**, then go to **System Settings → Privacy & Security** and click **Open Anyway**.
   Or run this in Terminal: `xattr -dr com.apple.quarantine "/Applications/Intelligent TODO.app"`
3. The welcome screen sets up Claude Code: it installs it if it's missing, and you sign in with **your own** Claude account. Turn on **Start at login**.
4. Add the widget: right-click the desktop → **Edit Widgets…** → search **Intelligent TODO**.

## Requirements
- macOS 26 (Tahoe) or later
- Claude Code with a Claude Pro or Max plan, or an API key

## Features
- A Liquid Glass desktop widget, where you can tick off tasks and start or pause timers
- **Voice:** click the mic and say your to-dos (speech is recognized on your Mac)
- **Ask Claude** (⌘K): add several to-dos at once, edit them ("remove that", "make it urgent"), or ask questions
- Study plans with official resource links, daily and weekly reviews, reminders, and time tracking
- Quick add from anywhere with ⌃⌥Space

## Privacy
- The app doesn't include or share anyone's credentials. It uses the Claude Code you have signed in on your own Mac.
- Your to-dos stay in `~/Library/Application Support/IntelligentTodo/`. The app's local server only listens on `127.0.0.1`.
