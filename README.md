# FlowLog (flog)

A simple terminal journal for developers.

FlowLog lets you track wins, bugs, ideas, and todos without leaving the command line. Everything is stored locally as plain Markdown files.

No accounts.
No cloud sync.
No subscriptions.
No telemetry.

Just logs.

---

## Example

```bash
flog log "Finished inventory system" -c Win
flog log "Quest menu crashes when opened" -c Bug
flog log "Add crafting system" -c Todo

flog standup
```

Output:

```text
📅 Standup Report

🛠️ Accomplished Today
- Finished inventory system

⚠️ Blockers/Debt
- Quest menu crashes when opened

🎯 Next Objectives
- Add crafting system
```

![Terminal](https://github.com/user-attachments/assets/c8fcbc52-9a6f-4604-b542-0d0cf397023b)

Or you can use the "flog" command that gets you into a dashboard

![Dashboard](https://github.com/user-attachments/assets/95fe516f-8794-411d-872d-976500999076)


---

## Features

* Interactive terminal dashboard
* Local-first storage
* Category tags
* Search through all logs
* Daily standup generation
* Historical navigation
* Plain Markdown storage

---

## Installation

1. Download `flowlog_app.zip`
2. Extract it
3. Add the folder containing `flog.exe` to your PATH
4. Open a new terminal
5. Run:

```bash
flog
```

On first launch, FlowLog creates:

```text
~/.flowlog
```

This folder stores all logs as Markdown files.

---

## Commands

```bash
flog
```

Open the interactive dashboard.

```bash
flog log "message" -c Win
```

Create a log entry.

```bash
flog search "keyword"
```

Search all logs.

```bash
flog view -d 7
```

View logs from 7 days ago.

```bash
flog standup
```

Generate a daily standup report.

---

## Storage

All data is stored locally.

Example:

```text
C:\Users\<YourName>\.flowlog\
```

Logs are saved as:

```text
2026-06-18.md
2026-06-19.md
2026-06-20.md
```

You own your data.

---

## Why?

I wanted a quick way to keep track of what I was doing while coding without opening a browser, note-taking app, or project manager.

So I made one.
