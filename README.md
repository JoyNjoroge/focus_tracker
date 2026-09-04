# focus-tracker

A single-page, terminal-styled focus tracker for people who start four things before finishing one.

## Why

Most task trackers assume you'll work through a list in order. This one assumes the opposite: you'll have five things competing for your attention at once, and a new thought (a related task, a tangent, a notification) will try to hijack whatever you're doing right now.

The rule it enforces: only one task can be "active" at a time. Everything else, whether it's the next item on your list or a random idea that just showed up, goes into a waiting queue instead of taking over. Switching what's active is a deliberate action, and it's counted, so you get an honest picture of your day instead of a vague feeling of having failed at all of it.

## Features

- **One active task at a time**, shown large with a live timer
- **A capture queue** for anything that pulls at your focus mid-task, so it gets recorded without interrupting what's running
- **Switch tracking**, not shaming, just a count of how many times focus moved
- **Pause/resume** without losing accumulated time on a task
- **A status line** with today's totals: time focused, tasks finished, switches, longest unbroken stretch
- **Local persistence**, your day is saved automatically and picks up where you left off
- **No build step, no dependencies.** It's one HTML file.

## Usage

Open `focus-tracker.html` in a browser. That's it.

1. Type what you're about to do into the input and hold it, or pull up something already in the queue to make it active.
2. Work. If something else comes to mind, type it into the queue instead of switching to it.
3. When you're ready to change tasks, pause or finish the current one, then switch to the next.
4. Use "reset --day" to clear the board and start fresh.

## Tech

Plain HTML, CSS, and JavaScript. No frameworks, no build tools, no external requests. State is kept in the browser's local storage, so nothing leaves your machine.

## License

MIT
