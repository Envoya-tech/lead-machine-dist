# 🚀 Lead Machine — macOS Installation Guide

**Time required:** 15–20 minutes (most of it is automatic)  
**What you need:** Your license key (sent by email from Envoya)

---

## Before you start

Have these ready — you'll enter them in the setup screen after install:

| What | Where to get it |
|---|---|
| **Lead Machine license key** | In your Envoya welcome email |
| **Anthropic API key** | [console.anthropic.com](https://console.anthropic.com/settings/keys) → Create Key |
| **Apollo.io API key** | [app.apollo.io](https://app.apollo.io) → Settings → API |
| **Brave Search API key** | [api.search.brave.com](https://api.search.brave.com/app/keys) → New Key |

---

## Step 1 — Download

Download the file `lead-machine-x.x.x.pkg` from the link in your Envoya welcome email.

It will appear in your **Downloads** folder.

---

## Step 2 — Open the installer

Double-click the `.pkg` file in your Downloads folder.

> ⚠️ **If macOS says "cannot be opened because it is from an unidentified developer":**
> 1. Open **System Settings** → **Privacy & Security**
> 2. Scroll down — you'll see a message about Lead Machine
> 3. Click **"Open Anyway"**
> 4. Double-click the `.pkg` again

Click **Continue** → **Install**. Enter your Mac password if asked. This is normal — the installer needs it to set up the database and background services.

---

## Step 3 — Wait for the installer

A black terminal window will appear and run automatically. You'll see progress messages — **don't close it.**

It installs everything Lead Machine needs (Python, PostgreSQL, etc.) — you don't need to install anything yourself.

When it's done, you'll see:

```
✓  Lead Machine is running
✓  Opening http://localhost:8080 …
```

Your browser opens automatically.

---

## Step 4 — Complete setup in your browser

The setup wizard opens at **http://localhost:8080/setup**

Enter:
1. Your **license key**
2. Your **Anthropic API key**
3. Your **Apollo API key** *(optional but needed for lead sourcing)*
4. Your **Brave Search API key** *(optional but needed for web research)*
5. Create your **admin account** (email + password — just for logging in)

Click **Finish Setup** — that's it.

---

## Step 5 — Start using Lead Machine

Lead Machine is now running at: **http://localhost:8080**

Bookmark that link. Open it anytime in your browser — it works even without internet (except for AI features).

---

## Starting Lead Machine after a restart

Lead Machine starts automatically when your Mac boots. You don't need to do anything.

If it ever doesn't load:
1. Open **Terminal** (search in Spotlight)
2. Type: `open http://localhost:8080`

---

## Something went wrong?

**If the installer stops mid-way:** Just run it again — it will automatically continue from where it stopped (you won't lose progress).

**If the page doesn't load:** Wait 30 seconds after the terminal window closes, then refresh.

**Still stuck?** Email **hello@envoya.tech** with a screenshot of the error message and we'll sort it out.
