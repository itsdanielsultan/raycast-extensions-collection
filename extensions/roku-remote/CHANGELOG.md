# Roku Remote Changelog

## [Keyboard Remote, Menu Bar & Search] - {PR_MERGE_DATE}

- Rebuilt **Roku Remote** around the keyboard: type W A S D / H J K L to move, Space for OK, Q for Back, P for play/pause and more; ⌥-arrow shortcuts work from any row.
- Added live **text mode** (⌘T) that mirrors what you type into the TV's text field.
- Added a **now playing** panel with app icon, playback state and progress.
- Added **Quick Launch** rows with real app icons, and turned *Launch Roku App* into an icon grid.
- New **Search Movies & Shows on Roku** command using Roku universal search.
- New **Roku Menu Bar** command.
- Volume ×5 / ×10 actions.
- Cached identity checks make repeated key presses roughly twice as fast; key presses no longer toast on success.


## [Initial Version] - {PR_MERGE_DATE}

- Control Roku TVs and players directly over the local network with discovery, multiple saved TVs, app/input launching, navigation, playback, volume, power, and text entry.
- Add a TV dashboard, configurable ordered routines, progress and cancellation, saved-routine Quicklinks, and previous-activity restoration.
- Add free deterministic English instructions, room/app aliases, explicit-name protection, and complete saved-routine step previews.
- Add optional Raycast AI status, single-use preview, confirmation, and execution tools; core commands work without an AI subscription.
- Validate device identity, capabilities, deadlines, ordering, bounded inputs, changed plans, and cancellation. Describe toggles and dynamic restore destinations explicitly.

See TESTING.md and RELEASE.md for exact verified scope and hardware/native integration limitations.
