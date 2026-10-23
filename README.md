# Hi, I'm Paul 👋

Mathematics and science teacher in New Zealand, and rowing coach. I build small, free, browser-based tools for my own classroom and share them here in case they're useful in yours.

The classroom tools and puzzle generators run in a web browser with nothing to install. Click a name to open the tool, or **code** to see how it works.

## Classroom tools

| Tool | What it does | |
|---|---|---|
| [**Classroom Manager**](https://ironstamp.github.io/classroom-tool) | A faster front end for Google Classroom: post and schedule work by period, publish drafts in bulk, and copy a whole course to a Google Sheet and back into a new one | [code](https://github.com/ironstamp/classroom-tool) |
| [**Group Allocator**](https://ironstamp.github.io/group-picker) | Randomly split a class into groups, with a reveal-one-at-a-time mode for the projector | [code](https://github.com/ironstamp/group-picker) |
| [**Score Tracker**](https://ironstamp.github.io/scoretracker) | Live projected leaderboard with +1/−1 buttons and a countdown timer | [code](https://github.com/ironstamp/scoretracker) |

## Maths puzzle generators

Type in question-and-answer pairs (with LaTeX for maths), then print a student copy and a separate teacher key.

| Tool | What it makes | |
|---|---|---|
| [**Tarsia Puzzle Generator**](https://ironstamp.github.io/tarsia-generator) | Triangle-matching jigsaws (6-piece hexagon or 9-piece triangle) | [code](https://github.com/ironstamp/tarsia-generator) |
| [**Domino Chain Puzzle Generator**](https://ironstamp.github.io/domino-puzzle-generator) | Domino-chain matching cards, with optional images | [code](https://github.com/ironstamp/domino-puzzle-generator) |

## Moving schools

Scripts you run on your own computer, for taking your work with you when you leave a Google Workspace school.

| Tool | What it does |
|---|---|
| [**Drive Backup**](https://github.com/ironstamp/drive-backup) | Copies your Google Drive (and chosen shared-drive folders) to your computer or a thumb drive as Word, Excel and PowerPoint files. Safe to re-run, and read-only on your Drive |
| [**Classroom archive**](https://github.com/ironstamp/drive-backup/blob/main/docs/classroom-archive.md) | Downloads every file attached to a Google Classroom course, so Classroom Manager can rebuild the course on another account |

Both use the free [rclone](https://rclone.org) tool; the Drive Backup README walks through setup step by step.

## Using these tools

All of them are free to use, share and adapt for education. The browser tools are single HTML files, so you can fork a repo and host your own copy on GitHub Pages, or just download the file and open it. Student names you type in stay in your browser and aren't sent anywhere (Classroom Manager talks only to your own Google account).

Found a bug or have an idea? Open an issue on the tool's repo.
