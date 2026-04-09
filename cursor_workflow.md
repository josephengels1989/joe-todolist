---
name: How to open Cursor with amp-manufacturing project
description: Step-by-step workflow to get Cursor running with the website project
type: feedback
---

## Opening Cursor with the Website Project

**DO NOT skip ahead.** Follow these steps exactly and in order.

### Step 1: Open Cursor App
1. Click the **Cursor cube icon** in the Dock (bottom of screen)
2. You'll see a login screen with "Sign Up" and "Log In" buttons

### Step 2: Log In
1. Click **"Log In"** button
2. Safari opens automatically
3. Log in with your email/password
4. After login, Safari confirms and Cursor app loads

### Step 3: Load Project
1. Cursor shows two buttons: "New project" and "Open project"
2. Click **"Open project"** (the folder icon)
3. Navigate to `/Users/joeshomefolder/Documents/amp-manufacturing`
4. Select it and open

### Step 4: Ready to Work
1. On the left: "New Chat" panel with text input
2. On the right: File tree showing all website files (HTML, CSS, blog, assets, etc.)
3. This is ready for editing

## Using Cursor to Edit the Website

1. **Describe what you want to change** in the left chat panel (e.g., "Change the hero title to 'Custom Inductors for Your Business'")
2. **Cursor suggests edits** and shows you the changes
3. **Click "Accept"** to apply the changes
4. **After any changes**, run in Cursor's terminal:
   ```
   npx vercel --prod --yes
   ```
5. **Then hard-reload Safari** with cache buster:
   ```
   osascript -e 'tell application "Safari" to activate' -e 'tell application "Safari" to set URL of current tab of front window to "https://ampmanufacturing.com/?v=TIMESTAMP"'
   ```
   (Use a unique timestamp each time, e.g., `?v=20260331`)

## Key Rule
**Do NOT assume Joe knows the next step.** Always ask what he sees on screen after each action, then give the NEXT concrete step. No skipping ahead, no assumptions.

**Why:** Joe gets frustrated by vague guidance. Be explicit.
