# Follow-up challenge: Leveraging Claude to maintain spreadsheets

**Work sample, Agueda Schwartz.** I wrote this after a staff AI forum session on Claude and spreadsheets, October 2026, so people would use what they learned while it was still fresh. It gives people one thing to try on a real spreadsheet that same week, at two levels so beginners and confident users both have a way in, and asks them to report back at the next session. Names are removed.

---

## The challenge

Pick a spreadsheet you already use, or a spreadsheet chore you do every week. This week, hand it to Claude. Try the Basic or the Advanced level.

Share what worked and what didn't in the AI Forum. At the next session, we'll ask who tried it.

## Three ways to get Claude's work into a spreadsheet

- **Paste (Claude chat or Claude Code):** ask Claude for tab-separated rows, then paste into the first cell of a Google Sheet. It splits into columns and rows on its own. Quick, but you do the pasting.
- **Claude in Chrome:** use it directly in the browser, or have Claude Code drive it. It edits the Sheet for you, but it's slow and needs watching.
- **Excel in Drive (Claude Code):** Claude writes to the file directly. Best for updates you make again and again.

## Basic (Claude chat or Claude Code)

### Option 1: Refine a Sheet you already have

- In Google Sheets, go to File > Download > Microsoft Excel (.xlsx).
- Upload the file to Claude chat, or point Claude Code to it.
- Paste this prompt:

> *Here's a spreadsheet I use for [what it's for]. Review it and suggest how to make it easier to keep up to date: better columns, formulas, cleanup, or anything I could stop doing by hand. Keep your suggestions short and practical, and ask me questions if anything is unclear.*

### Option 2: Paste rows into a Google Sheet

- Paste this prompt into Claude, filling in your columns and info:

> *Turn the following into rows for my spreadsheet. Columns, in order: [Column 1], [Column 2], [Column 3]. Give me the rows as tab-separated text with no header row, inside a code block so I can copy it.*
>
> *[paste or describe your info here]*

- Copy the result with the copy button on the code block.
- In your Google Sheet, click the first empty cell in column A and paste. It splits into columns and rows on its own.

Tip: the code block keeps the tabs. Without it, everything can paste into one cell.

## Advanced (Claude Code)

### Before you start

- Install Google Drive for desktop or OneDrive, so your files sync to your computer. That's how Claude Code can update the file.
- A file uploaded in the Drive browser is only a snapshot. Later updates won't reach Drive without the sync app.

### Build an Excel tracker and keep it updated

Start one:

> *Create an Excel tracker called [name] in my [synced Drive or OneDrive folder] with these columns: [columns]. Then add today's entry: [details].*

Or use the Sheet you downloaded in Basic, Option 1: save it into a synced folder and use it as your tracker from then on.

Keep it updated:

> *Add these updates to [file name]: [details]. Show me the rows you plan to add or change before you write them.*

### Rules that keep it working

- Keep it as Excel. Don't choose "Save as Google Sheets." That creates a second file, and the two drift apart without warning.
- Close the file everywhere before Claude updates it. If it's open, Drive can hit a sync conflict ("Can't sync your changes").
- Review before Claude writes. Ask it to show you the changes first.
- Have Claude make a backup before big changes.
- Your team can still open and edit the file in Google Drive, as long as it stays Excel.

## Share what you tried

Post in the AI Forum: what spreadsheet you picked, what you tried, and what worked or didn't. We'll check in at the next session.
