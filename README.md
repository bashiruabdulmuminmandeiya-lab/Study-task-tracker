# Student Study Task Tracker

A simple web application that helps a student keep track of study tasks and assignments.

**Author:** Bashiru Abdul-Mumin Mandeiya (Index No. 01250318C)
**Project:** ATU Virtual Internship - Software Development Individual Mini Project
**Institution:** Accra Technical University (ATU)
**Contact:** Bashiruabdulmuminmandeiya@gmail.com

**Live application:** https://bashiruabdulmuminmandeiya-lab.github.io/Study-task-tracker/
**GitHub repository:** https://github.com/bashiruabdulmuminmandeiya-lab/Study-task-tracker

## Problem
Students handle several courses at once, and tasks kept in notebooks or chat messages are easily forgotten. This app gives one place to record, view, complete and delete study tasks.

## Features
- Add a task with a title and a subject or course name
- Blank task titles are rejected with an error message
- Tasks are shown in a clear list with a "x of y completed" counter
- Mark a task complete and change it back to incomplete
- Delete a task
- Tasks stay saved after the page is refreshed (browser local storage)
- A helpful message appears when the list is empty
- **Extra feature:** High / Normal / Low priority and an All / Incomplete / Completed filter

## Technologies
HTML, CSS and JavaScript (no frameworks, no login, no database, no API keys).

## Project files
| File | Purpose |
|------|---------|
| `index.html` | Page structure: form, filter and task list |
| `style.css` | Layout and colours (works on phones and laptops) |
| `script.js` | Add, complete, delete, filter, validation and saving |

## How to run
Open `index.html` in any web browser, or visit the live link above.

## Testing
| Test | Result |
|------|--------|
| Add a task with a title | Pass |
| Submit an empty title | Pass |
| Mark a task complete / incomplete | Pass |
| Delete a task | Pass |
| Refresh the page | Pass |

## Security
The repository contains no passwords, private keys or other secrets.
