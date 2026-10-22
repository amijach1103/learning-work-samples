# Claude AI Setup Instructions
## For Pilot Participants

**Time needed:** 15-20 minutes
**Support:** Message me on Teams if you get stuck at any step

---

## What We're Setting Up

You'll be using **Claude AI** (the desktop app or browser version at claude.ai) with two integrations turned on:
- **Asana**, so Claude can read/update your tasks
- **Google Drive**, so Claude can read your documents

This is NOT Claude Code (the terminal version). Just regular Claude with some extra powers.

---

## Before You Start

You'll need:
- [ ] Your work email
- [ ] Access to Asana (you already have this)
- [ ] Access to Google Drive (you already have this)
- [ ] About 20 minutes of uninterrupted time

---

## Step 1: Access Claude AI

**If you already use Claude at work, skip to Step 2.**

### Option A: Desktop App (Recommended)
1. Download Claude for desktop if you haven't: [claude.ai/download](https://claude.ai/download)
2. Open the app and sign in with your work email
3. You should see your organization's workspace in the workspace selector

### Option B: Browser
1. Go to [claude.ai](https://claude.ai)
2. Sign in with your work email
3. You should see your organization's workspace in the workspace selector (bottom left)

**If you don't see your organization's workspace:**
- Check that you're using your work email, not personal
- If still stuck, message me on Teams. IT may need to add you

---

## Step 2: Turn On Asana Integration

This lets Claude read your tasks and help manage them.

### 2a. Open Integrations

1. In Claude, click your profile icon (bottom left)
2. Click **Settings**
3. Click **Integrations** (or **Connected Apps**)

### 2b. Enable Asana

1. Find **Asana** in the list
2. Toggle it **On** or click **Connect**
3. You'll be redirected to Asana to authorize
4. Click **Allow** to give Claude access to your Asana

### 2c. Verify It Worked

Start a new conversation and type:

```
What Asana workspaces do I have access to?
```

If Claude lists your workspaces, you're connected.

**If it doesn't work:**
- Try refreshing Claude
- Check that Asana shows as "Connected" in Settings
- Message me on Teams with a screenshot of what you see

---

## Step 3: Turn On Google Drive Integration

This lets Claude read your documents.

### 3a. Back to Integrations

1. Go to Settings → Integrations (same place as before)

### 3b. Enable Google Drive

1. Find **Google Drive** in the list
2. Toggle it **On** or click **Connect**
3. You'll be redirected to Google to authorize
4. Click **Allow** to give Claude access to your Drive

### 3c. Verify It Worked

Start a new conversation and type:

```
What Google Drive files do I have access to?
```

If Claude can see your Drive, you're connected.

**If it doesn't work:**
- Try refreshing Claude
- Check that Google Drive shows as "Connected" in Settings
- Message me on Teams with a screenshot of what you see

---

## Step 4: Test Both Connections

Let's make sure everything works.

### Test Asana

```
Look at my Asana tasks. What's due this week?
```

**What should happen:**
- Claude reads your Asana
- Shows you upcoming tasks and deadlines

### Test Google Drive

```
What documents have I worked on recently in Google Drive?
```

**What should happen:**
- Claude reads your Drive
- Shows you recent documents

**If either doesn't work:**
- Go back to Settings and check the connection
- Try disconnecting and reconnecting
- Message me on Teams if still stuck

---

## Step 5: Your First Real Task

Now that setup is done, try one real workflow:

### Option A: Get a Task Summary

```
Summarize my open tasks across all Asana projects. Group them by project and note which ones are overdue or due soon.
```

### Option B: Draft a Status Update

```
Based on my Asana tasks and recent Google Drive documents, draft a quick status update I could share with my team.
```

### Option C: Summarize a Document

```
Find [document name] in my Google Drive and give me a summary.
```

**Pick whichever feels most useful to your actual work right now.**

---

## Quick Reference: Common Prompts

Once you're set up, here are prompts you can use daily:

| What you want | What to say |
|---------------|-------------|
| See your week | "What's due this week in Asana?" |
| Daily priorities | "What should I focus on today based on my tasks?" |
| Status update | "Write a status update based on my Asana tasks and recent Drive docs" |
| Mark complete | "Mark [task name] as complete in Asana" |
| Add a task | "Add a task to [project]: [task description]" |
| Find blocked items | "What tasks are blocked or overdue?" |
| Summarize a doc | "Summarize [document name] from my Google Drive" |
| Find a file | "Find documents related to [topic] in my Drive" |

---

## Troubleshooting

### "Claude can't access my Asana"

1. Go to Claude Settings → Integrations
2. Check if Asana shows as Connected
3. If not, click Connect and re-authorize
4. If yes but still not working, try Disconnect → Reconnect

### "Claude can't access my Google Drive"

1. Go to Claude Settings → Integrations
2. Check if Google Drive shows as Connected
3. If not, click Connect and re-authorize
4. If yes but still not working, try Disconnect → Reconnect

### "I don't see Integrations in Settings"

- Make sure you're in your organization's workspace (not personal)
- Try refreshing the page
- Try the desktop app if you're using browser (or vice versa)
- Message me on Teams. Your account may need configuration

### "It asks me to authorize but then nothing happens"

- Try a different browser (Chrome recommended)
- Clear cookies and try again
- Check if popup blockers are interfering
- Try the desktop app instead

### "Claude is reading the wrong Asana workspace"

Tell Claude which workspace to use:
```
Use my [Workspace Name] workspace in Asana. What tasks are due this week?
```

---

## What's Next

Once setup is complete:

1. **This week:** Start using Claude + Asana + Drive in your real work
2. **Share in Teams:** Post what's working, what's confusing, what's broken
3. **Optional drop-in:** Weekly if you want live help

---

## Need Help?

- **Teams:** Message me directly (fastest response)
- **Email:** If Teams isn't working

**Don't spend more than 10 minutes stuck on any step.** Just message me on Teams and we'll figure it out together.

---

*Setup instructions v1.0, January 2026*
*Questions? Ping Agueda on Teams*
