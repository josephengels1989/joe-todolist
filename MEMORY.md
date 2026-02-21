# Joe's Project Memory

## Who Joe Is
- Owner of Ampersand/ANT Manufacturing (custom toroidal inductor manufacturer)
- Working with his dad on sales/business development strategy
- NK Technologies is his reference client ($15M-$30M, current sensors, San Jose)
- Has a developer friend helping with the website

## Hardware
- **MacBook Air** — primary machine
- **Samsung T9 SSD** — external backup drive, connected via USB, running **Time Machine** (hourly backups)

## Key Files & Locations
- **Website project:** `/Users/joeshomefolder/Documents/amp-manufacturing/` — deployed on **Vercel**, repo on **GitHub** (`josephengels1989/amp-manufacturing`). Also backed up on iCloud. ALWAYS `git pull origin main` first to get the latest version before working on it.
- **LIVE WEBSITE URL: `https://ampmanufacturing.com`** — This is the REAL production URL. DO NOT use `amp-manufacturing.vercel.app` (old/stale different Vercel account) or `ant.sailorskills.com` (also old/stale). The Vercel project is under `oldmanonthebench-7315s-projects`. After pushing to GitHub, always run `npx vercel --prod --yes` from the project directory to deploy, then open `ampmanufacturing.com` in Safari. Add `?v=date` cache buster if Safari shows stale content.
- **CRM (color-coded):** `/Users/joeshomefolder/Documents/AMP-Business/AMP_CRM 3.numbers`
- **Reorganized CRM:** `/Users/joeshomefolder/Documents/AMP-Business/AMP_CRM_Reorganized.csv`
- **Sales outreach folder:** `/Users/joeshomefolder/Documents/AMP-Business/Sales-Outreach/`
- **Deep dive report (formatted):** `Sales-Outreach/Bay_Area_Deep_Dive.html`
- **Reading log spreadsheet:** `/Users/joeshomefolder/Documents/Reading_Log.csv`
- **Printable bookmark cards:** `Sales-Outreach/Reading_Bookmark_Card.html`
- **Homemade Supermemo (SM-2 spaced repetition):** `/Users/joeshomefolder/Documents/Homemade Supermemo/index.html` — SuperMemo-equivalent flashcard app for reading notes. Runs in Safari, data in localStorage. On GitHub: https://github.com/josephengels1989/Homemade-Supermemo

## Reading Log System
- Joe is tracking reading hours with a physical bookmark card + Numbers spreadsheet
- **Current goal: 10 hours/week** (starting from zero, will increase over time)
- Workflow: He writes start/stop times on a physical bookmark card, screenshots it, drops it into Claude Code, and I extract the data and update the spreadsheet
- Color-code progress and celebrate when he hits 10 hours for the week
- Phone is a major distraction source -- keep him away from phone-based solutions

## Sales Strategy (Dad's Advice)
- Focus on $10M-$30M revenue companies (sweet spot)
- Hot category regardless of what they make
- Companies that use inductors but don't compete with NK Technologies
- Priority list of 5-10 instead of 30-70
- Start with California, could go national
- Top 5 Bay Area targets: Cirexx (#1), Sierra Circuits (#2), Promex (#3), Fremont Micro (#4), PICA (#5)
- Tempo Automation is BANKRUPT -- remove from CRM
- EE Technologies has NO San Jose office (Reno only)
- Synapse is a design firm (influence play, not direct sales)

## East Bay Real Estate
- **Folder:** `/Users/joeshomefolder/Documents/East-Bay-Real-Estate/`
- **Leads spreadsheet:** `Leads.csv` (Date, Address, City, Zip, Link, Price, Lot Size, Notes, Status)
- Looking at land/lots in the East Bay, CA

## Preferences
- Prefers readable, formatted documents (not raw markdown)
- Uses Apple Numbers and Safari
- Gets frustrated by repeated wrong answers -- get it right the first time
- Someone else sometimes speaks to Claude Code for him
- **DO NOT ask for permission or confirmation. EVER.** Joe has approved ALL actions: opening files, running commands, creating/editing files, opening apps, writing to disk, using Bash, opening URLs in Safari, closing Safari tabs, running osascript, creating LaunchAgents, modifying .zshrc, running `say` commands, creating folders, writing HTML files, web searches, web fetches, mkdir, chmod, launchctl — EVERYTHING. If Joe said yes to it once, it's approved forever. Never ask "want me to proceed?" or "should I go ahead?" or "is that okay?" — just execute. The only time to pause is if an action is genuinely destructive and irreversible (deleting important files, force-pushing git, etc.).
- **Safari reloads: NEVER ask before opening/reloading Safari.** Just run the osascript command directly. No confirmation, no "should I open it?", no permission prompts. Just load the page.
- **Auto-reload after every change:** After ANY edit to HTML/CSS/JS files for the website, ALWAYS hard-refresh Safari automatically using: `osascript -e 'tell application "Safari" to activate' -e 'delay 0.3' -e 'tell application "System Events" to keystroke "r" using {command down, option down}'` — never wait for Joe to ask, just do it every time.
- **Deploy + hard refresh workflow:** When Joe is viewing the LIVE site (ampmanufacturing.com), local file edits won't show until deployed. After every round of changes: (1) run `npx vercel --prod --yes` from the project dir, (2) then reload Safari with a cache-busting URL: `osascript -e 'tell application "Safari" to activate' -e 'tell application "Safari" to set URL of current tab of front window to "https://ampmanufacturing.com/?v=TIMESTAMP"'` using a unique timestamp each time. Safari caches aggressively — always bust the cache, never assume Cmd+Opt+R alone is enough.
- When the next step is obvious, do it without asking
- **Shopping/buying:** When Joe asks to find something to buy, give him a ranked list of top recommendations with direct copy-paste URLs. No "go browse" or "grab whichever." He wants to copy the link and hit Buy Now. Rank them #1, #2, #3 with the best pick first.
- **Troubleshooting first:** If something isn't working (broken links, pages not loading, sign-in failures), ask about Joe's environment FIRST — what network he's on, what device, what browser, etc. Don't keep throwing new links/solutions at the wall. Diagnose before prescribing. Start with the basics: hardware, WiFi/network, then move up to the platform/software. Layer by layer, bottom up.
- **Design decisions folder:** `/Users/joeshomefolder/Documents/amp-manufacturing/design-decisions/` — when we make a website design choice backed by research or reasoning, add it to this folder. When a new research-backed decision comes up during website work, REMIND Joe to add it to the design-decisions folder.

## TODO List
- **LinkedIn content system:** Create an automatic algorithm for Ampersand posts on LinkedIn. Ampersand should always be posting (every few days or every week). Create LinkedIn posts with credible, on-brand content.
- **Old iCloud account:** Get access to old iCloud account
- **Letters:** Write letters to Ash Oakley and Lisa D ahead of Joe's birthday
- **Regina Baker:** Decide on gift for Regina Baker and send her a letter
- **Aunt Eileen:** Return Aunt Eileen's package with my own package
- **Aunt Eileen (ASAP):** Purchase drugs for Aunt Eileen
- **Karina:** Congratulate Karina and send her money
- **Nick:** Repay Nick for South Dakota trip
- **S Corp:** Convert Ampersand to an S corp
- **Legal & Accounting:** Find legal and accounting for Ampersand
- **Rice & corn research:** Research arsenic in rice and American corn flour health
- **Charles Schwab:** Open business account with Charles Schwab
- **John Gray:** Discuss John Gray the philosopher and his books (come back to this)
- **Ampersand growth prediction:** Use the process from p.190 of *Thinking, Fast and Slow* (Kahneman) to predict growth of Ampersand. Work with Claude on this.
- **Send email on financial projections:** Send financial projections email
- **Schwab meeting prep:** Gather all documentation for the Charles Schwab branch meeting. (Status: 50% complete)
  - ✅ LLC Amendment: Filed to add Joseph V. Engels as co-owner (50/50 with Khuyen) — pending both signatures
  - ✅ Certificate of Good Standing: Ordered from CA Secretary of State (ready to print from portal, not yet printed)
  - ✅ Owner Information Document: Created professional form at `/Users/joeshomefolder/Documents/AMP-Business/Schwab_Owner_Information.html` (warm orange theme, MM/DD/YYYY dates)
  - ⏳ EIN Letter: Call IRS (1-800-829-4933) to request official EIN letter — do this tomorrow morning
  - ⏳ Owner Information Document: Fill out with Joseph V. Engels & Khuyen V. Nguyen info, print 2 copies
  - ⏳ Business Activity Info: Prepare numbers on monthly transactions, deposits, withdrawals, and account usage
    - How many customer orders/transactions per month?
    - Average order value?
    - Expected monthly revenue total?
    - Typical monthly deposits (from customers)?
    - Typical monthly withdrawals (paying suppliers/vendors)?
    - Do you and Khuyen have employees, or just you two?
    - Will you need payroll processing through Schwab?
    - Primary account use: operating account, vendor payments, customer deposits, etc.?
  - ⏳ Schedule Schwab meeting and gather final documents
- **Regression to the mean:** Do a deep dive on regression to the mean so I fully understand it. Work with Claude on this.
- **Agent building:** Dialogue with Claude about how to build an agent
- **Bank statement agent:** Build an agent to review Ampersand's bank statements
- **Order tracking:** Create spreadsheets to track Ampersand's orders
- **Income & expenses:** Create spreadsheets to track Ampersand's income and expenses
- **Flashcard system:** ✅ BUILT — SM-2 spaced repetition flashcard app at `/Users/joeshomefolder/Documents/Flashcards/index.html`. Add cards from reading, review daily.
- **Kasturi Gandhi:** (details TBD)
- **Regina Blumquist:** (details TBD)

## Books Wish List
- **The Life of Samuel Johnson** — James Boswell (Everyman's Library hardcover edition) ✅ ORDERED

### Not Yet Ordered
- **A Random Walk Down Wall Street** — Burton Malkiel (hardcover)
- **Notes from Underground** — Dostoevsky (Pevear & Volokhonsky translation, hardcover). Check Friends of Berkeley Public Library first: (510) 841-5604
- **Crime and Punishment** — Dostoevsky (Pevear & Volokhonsky translation, hardcover). Check Friends of Berkeley Public Library first
- **The Opposing Shore** — Julien Gracq (Taleb's favorite novel)
- **Meditations** — Marcus Aurelius (Gregory Hays translation)
- **The Prince** — Machiavelli (Harvey Mansfield translation, U of Chicago Press)
- **The Captive Mind** — Czesław Miłosz (translated by Jane Zielonko)
- **New and Collected Poems 1931–2001** — Czesław Miłosz (translations by Miłosz, Robert Hass, Robert Pinsky et al., Ecco/HarperCollins)
- **Native Realm** — Czesław Miłosz (translated by Catherine S. Leach)
- **The Issa Valley** — Czesław Miłosz (translated by Louis Iribarne)
- **Miłosz's ABCs** — Czesław Miłosz (translated by Madeline Levine)
- **The Silence of Animals** — John Gray
- **Black Mass: Apocalyptic Religion and the Death of Utopia** — John Gray
- **False Dawn: The Delusions of Global Capitalism** — John Gray
- **Seven Types of Atheism** — John Gray
- **Feline Philosophy: Cats and the Meaning of Life** — John Gray
- **Gray's Anatomy: Selected Writings** — John Gray
- **The Halo Effect** — Phil Rosenzweig
