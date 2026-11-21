# ToDo Flow

A fast, clean, and responsive to-do workspace built with plain HTML, CSS, and JavaScript. TaskFlow helps you organize daily work, track priorities, break tasks into subtasks, and stay focused with a built-in Pomodoro timer.

[![HTML](https://img.shields.io/badge/HTML-5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS-3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/docs/Web/JavaScript)
[![License](https://img.shields.io/badge/license-not%20specified-lightgrey)](#license)

## Features

- **Task management** — add, edit, complete, pin, and delete tasks
- **Subtasks** — split larger tasks into smaller, actionable checklist items
- **Priorities** — organize work as high, medium, or low priority
- **Categories** — filter tasks across Work, Personal, Study, Health, and Shopping
- **Smart views** — quickly browse all tasks, today's tasks, upcoming tasks, high-priority tasks, or completed tasks
- **Due dates** — highlight overdue work and track deadlines
- **Search and sorting** — find tasks by title, notes, or category and sort by date, priority, title, or creation time
- **Pomodoro timer** — start a 25-minute focus session or 5-minute break from the sidebar
- **Progress overview** — view totals, pending work, completed work, overdue tasks, and completion percentage
- **Theme support** — switch between light and dark modes
- **Sound controls** — enable or mute completion and timer sounds
- **JSON backup** — export your tasks and import them later
- **Local persistence** — tasks and preferences are stored in the browser with `localStorage`
- **Responsive interface** — works across desktop, tablet, and mobile screens
- **No build step** — open and run the app directly in any modern browser

## Run Locally

### Option 1: Open directly

1. Download or clone this repository.
2. Open `index.html` in a modern browser.

```bash
git clone https://github.com/Mohitmourya22/ToDo_Flow.git
cd ToDo_Flow
```

### Option 2: Use a local server

Using Python:

```bash
python3 -m http.server 5500
```

Then visit <http://localhost:5500>.

Using Node.js:

```bash
npx serve .
```

## How to Use

1. Enter a task title in the input field.
2. Choose its priority, category, and due date.
3. Add optional notes for extra context.
4. Press **Enter** or select **Add Task**.
5. Use the task actions to edit, pin, focus on, or delete a task.
6. Expand a task and use **+ Subtask** to create checklist items.
7. Use the sidebar views and category filters to narrow down the task list.

### Keyboard Shortcuts

| Shortcut | Action |
| --- | --- |
| `/` | Focus the search field |
| `Enter` | Submit a new task |
| `Escape` | Close the task edit modal |

## Data Storage and Backup

TaskFlow stores data locally in the current browser:

- Tasks: `taskflow_tasks_v2`
- Theme preference: `taskflow_theme_v2`
- Sound preference: `taskflow_sound_v2`

Use **Export** to download all tasks as a JSON backup and **Import** to restore an existing backup.

> Clearing browser data or using another browser/device can remove or separate locally saved tasks.

## Project Structure

```text
ToDo_Flow/
├── index.html    # Application markup, styles, and JavaScript
└── README.md     # Project documentation
```

## Built With

- Semantic HTML5
- CSS3 custom properties and responsive layouts
- Vanilla JavaScript
- Browser `localStorage`
- Web Audio API
- Browser File and Blob APIs

No external JavaScript framework or package installation is required.

## Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch:

   ```bash
   git checkout -b feature/your-feature
   ```

3. Make your changes and test them in a browser.
4. Commit and push your branch.
5. Open a pull request describing the improvement.

Please keep changes consistent with the existing plain HTML/CSS/JavaScript structure.

## License

No license has been specified for this repository. If you plan to reuse or redistribute the project, contact the repository owner for permission.

## Author

Created and maintained by [Mohit Mourya](https://github.com/Mohitmourya22).
