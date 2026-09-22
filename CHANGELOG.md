# Recent updates

Selected release highlights, newest first. The [website changelog](https://ponymux.com/changelog/) is the main release history and includes version downloads.

## 0.10.1

- Search now discovers all matching sessions — results load progressively so no matches are missed, even for common terms.
- Clicking a search result for an ended Terminal shows the matched transcript with highlights instead of opening a new shell.
- Resume in search mode targets the matched session. The banner shows the session name and date so you know which conversation you're resuming.
- Ended Terminals that previously auto-opened a shell now show their last conversation with Resume / Shell Only options.
- Transcript text size increased from 11pt to 12.5pt for easier reading.

## 0.10.0

- Search across your conversation history with Claude Code and Codex — find any topic you've discussed, even in sessions you closed weeks ago.
- Ended Terminals show the last conversation instead of a static screen capture. Matching messages are highlighted when navigating from search.
- Codex conversations are indexed alongside Claude Code transcripts.
- New conversations are picked up within seconds via filesystem events.
- Manage transcript index status, pause/resume, and rebuild from the new Transcript Index settings page.

## 0.9.2

- Search within the current Terminal with ⌘F, or filter Terminals by keyword with ⌘K.
- Faster switching and smoother scrolling with many Terminals open.
- Suspended agent sessions stay visible while resuming; the Clear button appears on hover.
- Drag-and-drop install with the Applications shortcut in the DMG.
- Fixed ⌘F and ⌘K search fields not receiving focus on open.
- Fixed search bar height shifting when typing.

## 0.9.0

- Terminal search view with ⌘K. Multi-token matching against Terminal names, prompts, recaps, and replies with scope pills for All, Terminals, and Archive.
- Cross-provider handoff between Claude Code and Codex. PonyMux extracts recent turns and a summary into a handoff file for the target provider.
- Quieter updates — Sparkle no longer shows a modal dialog. A sidebar button appears when a new version is ready.
- Session summary on wake — sleeping Terminals show the agent name, last activity, and a recap before you resume.
- Suspended agents survive restarts and restore on launch.
- Help menu with documentation links, feedback, and a What's New item.

## 0.8.0

- Read Markdown files beside your Terminal, including local inline images. Navigate between files, pin useful ones, and see edits update live.
- Let Claude Code or Codex open a file in your side panel with `pony open`.
- Get command-specific help with `pony help <command>` and check the app version with `pony --version`.
- Updated the terminal engine to reduce memory use and background GPU work, improve keyboard compatibility, and fix a rare freeze.

## 0.7.0

- Follow the macOS light or dark appearance automatically.
- Release GPU memory when Terminals are off screen.
- Create a Terminal while browsing Archive, Trash, or Agents.

## 0.6.0

- Find Terminals with live agents through the Agents sidebar entry.
- Choose your own reaction presets and resize the Inspector.
- Recognize sleeping sessions through the zzz badge and see the auto-resume countdown.
- Search the system symbol catalog when choosing an icon.
- Hold Back or Forward to jump through recent navigation history.

## 0.5.0

- Expanded VoiceOver support across Terminal rows, the sidebar, sessions, and Inspector.
- Added a History menu for recently visited Terminals.
- Simplified settings labels and made controls more consistent.

## 0.4.0

- Added Terminal settings for fonts, the cursor, screen effects, and shell options.
- Updated the Ghostty engine, including faster CJK text reflow.
- Added a background update checker and sidebar update button.

## 0.3.0

- Introduced a unified toolbar and browser-style Back and Forward navigation.
- Made the Inspector an independent resizable column.
- Added animated session pets.
