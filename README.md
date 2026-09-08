FocusMaster Pro 🎯

FocusMaster Pro is a standalone, browser-based productivity application that combines advanced timeboxing, agile project management, and consistency tracking into a single, elegant interface.

Built as a single HTML file, it requires zero build steps, no local server, and no complex dependencies. It runs entirely in your browser using React, Babel Standalone, and Tailwind CSS.

✨ Features

📊 Dashboard Analytics: Get a high-level view of your current streak, task completion rate, and total focus hours.

⏱️ Contextual Focus Timer: A built-in timeboxing engine (Pomodoro-style) that tracks what type of work you are doing using a color-coded methodology.

📋 Agile Project Pipeline (Kanban): Create projects and manage tasks across a Kanban board (To Do, In Progress, Completed). Features full CRUD (Create, Read, Update, Delete) capabilities.

🔥 90-Day Consistency Matrix: A dynamic, GitHub-style heatmap that tracks your cognitive allocation over the last 90 days. It updates automatically as you interact with tasks.

💾 Data Management:

CSV Export: Download your tasks to a spreadsheet for external reporting.

JSON Backup & Restore: Export your entire workspace (Projects, Tasks, and Consistency Data) to your local machine and restore it at any time.

🧠 The Methodology (The Legend)

FocusMaster Pro encourages you to categorize your tasks and time into five distinct types of cognitive load:

🟣 Deep Work: Uninterrupted, high-cognitive demand tasks. Critical path items.

🔵 Shallow Work: Logistical, non-demanding tasks. Routine execution.

🟠 Collaboration: Meetings, syncs, reviews, and stakeholder management.

⚪ Admin/Overhead: Bureaucracy, organization, and documentation.

🟢 Rest/Recovery: Mandatory downtime to maintain long-term velocity.

🚀 How to Run Locally

Because the app is entirely self-contained, running it is incredibly simple:

Clone or download this repository.

Double-click the index.html file to open it in your preferred web browser (Chrome, Firefox, Safari, Edge, etc.).

That's it!

Note: Since this is a client-side application running without a database, your data lives in the browser's current session. Be sure to use the Data Management tab to export your Backup JSON file before closing the tab if you want to save your progress!

🌐 How to Deploy to GitHub Pages

You can host this application for free on GitHub Pages in just a few minutes:

Create a new repository on GitHub.

Upload the index.html file to the root of the repository.

Go to the repository's Settings tab.

On the left sidebar, click on Pages.

Under Build and deployment > Source, select Deploy from a branch.

Under Branch, select main (or master), and click Save.

Wait a minute or two, and GitHub will provide you with a live, shareable URL to your app!

🛠️ Tech Stack

React 18 (Loaded via CDN)

Tailwind CSS (Loaded via CDN for rapid UI styling)

Babel Standalone (Compiles JSX directly in the browser)

Lucide Icons (Custom SVG implementations to keep the file standalone)
