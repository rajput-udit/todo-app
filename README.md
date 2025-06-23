# Todo Application

A beautiful, modern, and feature-rich Todo List web application built with HTML, CSS (Bootstrap 5), and vanilla JavaScript.

## Features

- Add, edit, complete, and delete tasks
- Set reminders for tasks (with browser notifications)
- Assign priority (Low, Medium, High) to each task
- Sort tasks by priority or due date
- Responsive design with light/dark mode toggle
- Table view with pagination for large lists
- Persistent theme preference (localStorage)
- Modern UI with Font Awesome icons and Bootstrap styling

## Getting Started

1. **Clone or Download** this repository to your local machine.
2. **Open** `todo_app.html` in your web browser (no server required).

## Usage

- Enter your task in the input field and click **Add Task** or press Enter.
- Optionally, set a reminder date/time and select a priority.
- Click the checkmark to complete/undo a task, the pencil to edit, or the trash to delete.
- Use the sort dropdown to organize your tasks.
- Switch between list and table views for better management.
- Toggle dark mode using the switch in the header.

## Browser Notifications

- The app will request permission to show notifications for reminders.
- If granted, you'll receive a notification when a task's reminder time is reached.

## Customization

- All styles are in the `<style>` section of `todo_app.html`.
- You can further customize the look and feel by editing the CSS variables or Bootstrap classes.

## Dependencies

- [Bootstrap 5](https://getbootstrap.com/)
- [Font Awesome 6 Free](https://fontawesome.com/)

All dependencies are loaded via CDN—no installation required.

## License

This project is open source and free to use for any purpose.
