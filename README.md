# Raycast Extensions

A collection of 19 [Raycast](https://raycast.com) extensions for macOS, built around the apps and devices I actually use.

| Extension | What it does | Commands |
| --- | --- | --- |
| [Affinity Document Inspector](extensions/affinity) | Inspect open Affinity documents and layers through Affinity’s local MCP server. | 1 |
| [Alter Actions](extensions/alter-actions) | Run your saved Alter actions with selected text, clipboard text, or a custom prompt after reviewing the input. | 1 |
| [Beeper Follow-Ups](extensions/beeper-follow-ups) | Review direct conversations whose latest visible message came from someone else and prepare a draft in Beeper. | 2 |
| [Brain.fm](extensions/brain-fm) | Control the Brain.fm web player and see the current track, timer, and browser media session. | 7 |
| [Caps Lock](extensions/caps-lock) | Toggle Caps Lock even when your Caps Lock key is remapped to Hyper, Escape, Control, or another key. | 4 |
| [Google Classroom](extensions/classroom) | See what's due, what's missing and what's graded across your Google Classroom courses. | 4 |
| [Cleft Notes](extensions/cleft-notes) | Search Cleft's synced notes and transcripts, and control voice capture using native Cleft Shortcuts actions. | 6 |
| [Cluely](extensions/cluely) | Browse Cluely meetings, filter recent sessions, and copy summaries and transcripts through the official CLI | 2 |
| [Cotypist](extensions/cotypist) | Read and control Cotypist default completions through its native Accessibility controls | 4 |
| [Downie](extensions/downie) | Send URLs to Downie with per-download audio, MP4, extraction, and destination options. | 3 |
| [Fleeting Notes](extensions/fleeting-notes) | An instantly editable scratchpad that saves as you type and resumes where you left off. | 4 |
| [Highlight AI](extensions/highlight) | Open Highlight's native search and start new chats or task capture using its documented Mac controls. | 1 |
| [LaunchOS Layout Search](extensions/launchos-layout-search) | Search the apps, custom aliases, folders, and pages in your LaunchOS layout without changing it. | 1 |
| [Microsoft Word](extensions/microsoft-word) | Inspect the active Word document, copy text, control Track Changes, and create a document from text. | 4 |
| [Plasticity Model Inspector](extensions/plasticity) | Search the open Plasticity model and inspect objects through its official Blender bridge. | 1 |
| [Roku Remote](extensions/roku-remote) | Fast, keyboard-driven control for Roku TVs and players over your local network — now playing, app launching, search, routines and a menu bar. | 18 |
| [Spokenly Word Replacements](extensions/spokenly-word-replacements) | Search, add, remove, and back up Spokenly word replacements through its official CLI | 2 |
| [Sunflower](extensions/sunflower) | Control Sunflower's disk analysis views, rescan the current disk, and navigate a completed scan from Raycast | 3 |
| [WikiHow](extensions/wikihow) | Find wikiHow articles and read search excerpts in Raycast using your Brave Search API key | 1 |

## Highlights

- **Roku Remote**: a keyboard-driven remote. Type `W A S D` to move, `Space` for OK and `P` to play or pause. It also has live text entry into TV search fields, a now-playing panel with real app icons, one-key app launching, universal search and a menu bar.
- **Google Classroom**: what's missing, due today or due this week, with turned-in and graded status and a menu bar counter.
- **Beeper Follow-Ups**: conversations waiting on your reply, with *Mark as Handled* and a menu bar count.
- **Caps Lock**: toggle, force on or off, and a menu bar indicator, even when the physical key is remapped.

## Install an extension locally

```bash
git clone https://github.com/itsdanielsultan/raycast-extensions-collection.git
cd raycast-extensions-collection/extensions/roku-remote
npm install
npm run dev
```

`npm run dev` imports the extension into Raycast in development mode. Each folder is a standalone extension with its own `package.json`, README and tests (`npm test`).

Caps Lock compiles a small Swift helper, so building it needs full Xcode, not just the Command Line Tools.

## License

MIT. See each extension's `LICENSE`. These are unofficial integrations and are not affiliated with Roku, Google, Beeper, Microsoft or any other vendor mentioned.
