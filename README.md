# Interactive Project Management Chart

A powerful, browser-based Gantt Chart Generator for planning and tracking project progress. Built with pure HTML, CSS, and JavaScript — no server required.

![Gantt Chart Preview](https://img.shields.io/badge/Version-1.0-blue) ![License](https://img.shields.io/badge/License-MIT-green) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🌐 Live Demo

**[View Live Demo →](https://jennysscameron.github.io/Interactive-Project-Management-Chart/)**

## ✨ Features

### Core Functionality
- **📊 Interactive Gantt Chart** — Visual timeline of all project tasks
- **✅ Task Management** — Create, edit, and delete tasks with ease
- **🚩 Milestone Support** — Mark important project milestones
- **📈 Progress Tracking** — Track completion percentage for each task
- **🎨 Color Coding** — Assign custom colors to tasks for better organization

### Views & Navigation
- **📅 Multiple Views** — Switch between Month, Week, and Day views
- **📆 Custom Date Range** — Set your project's start and end dates
- **📍 Today Indicator** — Visual marker showing the current date
- **🔍 Tooltip Details** — Hover over tasks for detailed information

### Data Management
- **💾 Auto-Save** — Data automatically saved to browser's local storage
- **📤 Export to JSON** — Export your project data as a JSON file
- **📤 Export to Excel** — Export your project data as an Excel workbook (.xlsx)
- **📥 Import Data** — Import previously exported JSON files
- **🗑️ Clear All** — Reset and start fresh

### Excel Export Features
The Excel export creates a professional workbook with two sheets:

| Sheet | Contents |
|-------|----------|
| **Gantt Chart Tasks** | Task Name, Type, Start/End Dates, Duration, Progress, Status, Color, Description |
| **Summary** | Total Tasks, Completed Tasks, In Progress Tasks, Overall Progress, Date Range, Export Date |

## 🚀 Getting Started

### Option 1: Use Online
Simply visit the [live demo](https://jennysscameron.github.io/Interactive-Project-Management-Chart/) — no installation required!

### Option 2: Download & Run Locally
1. Download or clone this repository
2. Open `index.html` in any modern web browser
3. Start adding your tasks!

```bash
git clone https://github.com/JennySSCameron/Interactive-Project-Management-Chart.git
cd Interactive-Project-Management-Chart
# Open index.html in your browser
```

## 📖 How to Use

### Adding Tasks
1. Click the **"Add Task"** button
2. Enter task name, start date, and end date
3. Set the progress percentage (0-100%)
4. Choose a color for the task
5. Optionally add a description
6. Click **"Save Task"**

### Adding Milestones
1. Click the **"Add Milestone"** button
2. Enter milestone name and date
3. Milestones appear as diamond markers on the chart

### Editing Tasks
- Click on any task bar in the Gantt chart, OR
- Click the edit icon (✏️) in the task list sidebar

### Changing Views
Use the view toggle buttons to switch between:
- **Months** — Best for long-term projects
- **Weeks** — Good for medium-term planning
- **Days** — Detailed view for short-term tasks

### Exporting Data

#### Export to JSON
- Click **"Export JSON"** to download your project data
- Use this for backup or transferring between browsers

#### Export to Excel
- Click **"Export Excel"** to download as `.xlsx` file
- Opens directly in Microsoft Excel, Google Sheets, or LibreOffice Calc
- Includes a summary sheet with project statistics

### Importing Data
1. Click **"Import"**
2. Select a previously exported JSON file
3. Confirm to replace current data

## 🎨 Task Status Colors

| Status | Color | Description |
|--------|-------|-------------|
| In Progress | Blue | Task is currently being worked on |
| Completed | Green | Task is 100% complete |
| Delayed | Red | Task end date has passed but not complete |
| Milestone | Yellow | Important project milestone |

## 💻 Technical Details

### Built With
- **HTML5** — Structure
- **CSS3** — Styling with CSS Variables
- **Vanilla JavaScript** — No framework dependencies
- **[SheetJS](https://sheetjs.com/)** — Excel export functionality
- **[Font Awesome](https://fontawesome.com/)** — Icons

### Browser Support
- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Opera

### Data Storage
All data is stored locally in your browser using `localStorage`. This means:
- ✅ Your data stays private on your device
- ✅ No account or login required
- ✅ Works offline
- ⚠️ Clearing browser data will delete your projects (use Export to backup!)

## 📁 Project Structure

```
Interactive-Project-Management-Chart/
├── index.html          # Main application file (all-in-one)
└── README.md           # This documentation file
```

## 🤝 Contributing

Contributions are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- [SheetJS](https://sheetjs.com/) for Excel export capabilities
- [Font Awesome](https://fontawesome.com/) for beautiful icons

---

<p align="center">
  Made with ❤️ for project managers everywhere
  <br>
  <a href="https://jennysscameron.github.io/Interactive-Project-Management-Chart/">View Demo</a>
  ·
  <a href="https://github.com/JennySSCameron/Interactive-Project-Management-Chart/issues">Report Bug</a>
  ·
  <a href="https://github.com/JennySSCameron/Interactive-Project-Management-Chart/issues">Request Feature</a>
</p>

