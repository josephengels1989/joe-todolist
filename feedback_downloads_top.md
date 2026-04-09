---
name: Downloads file visibility
description: Always touch/re-save email files in Downloads so they appear at the top of the stack
type: feedback
---

When writing emails or any files to the Downloads folder, always `touch` the file after writing so it has the latest timestamp and appears at the top of the Downloads stack in the Dock.

**Why:** Joe couldn't find the email file because it wasn't showing at the top of Downloads.

**How to apply:** After every file write to ~/Downloads, run `touch` on it to ensure it sorts to the top.
