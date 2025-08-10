# Anusual Flow

Anusual Flow is a web-based dashboard for communication agencies. It allows the General Manager to publish tasks and the creative team to pick up and complete them.

## Features

- **Public To-Do board**: The General Manager creates tasks visible to all creatives. Each task can include client name, due date, detailed brief, optional assignments.
- **Creative workflow**: Creatives can assign themselves tasks, mark tasks as completed, or create their own tasks when needed.
- **Completed work**: Completed tasks appear in a separate “Lavori effettuati” section with completion date and performer.
- **Notifications**: When a task is assigned, the assignee receives a WhatsApp or email notification with the task details.
- **Anagraphics**: The GM can manage client and team information via a dedicated modal menu.
- **Search & export**: Filter tasks and completed work by client and date; export filtered results to CSV for invoicing.
- **Login & registration**: Built-in authentication for creatives. A default GM account is provided (`info@anusual.it` / `Bonvini2022`).

## How to run

Anusual Flow is a single-page application with no server dependencies.

1. Clone this repository or download it as a ZIP.
2. Open `index.html` in a modern browser (Chrome or Edge).
3. To host on GitHub Pages, commit changes to the `main` branch (as this repository does) and enable Pages from the repository settings.

## Development

All logic is contained in `index.html`. The app uses:
- `localStorage` and `IndexedDB` for persistence.
- Built-in Speech Recognition API and MediaRecorder API for voice notes.
- No external libraries or frameworks.

Feel free to customize the interface (e.g., colours, fields) by editing the HTML and JavaScript.

## License

This project is provided as-is under the MIT License. See `LICENSE` for details.
