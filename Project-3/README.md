# Kanban Board

A simple and interactive **Kanban Board** built with HTML, CSS, and JavaScript.

The project allows users to organize tasks into different workflow columns and uses an API to store and retrieve task data.

## Live Demo

**[Organize yourself]()**

## Preview

![Preview]()

## Features

- Add new tasks
- Edit existing tasks
- Delete tasks
- Move tasks between columns
- Organize tasks into:
  - To Do
  - In Progress
  - Done
- Grab and Put tasks using an API
- Responsive design
- Dynamic UI updates without refreshing the page

## Technologies

- **HTML5**
- **CSS3**
- **JavaScript**
- **HTML Drag and Drop API**

## Project Structure

```text
Project-3/
│
├── index.html
├── style.css
├── script.js
├── README.md
└── assets/
    └── ...
```

## How It Works

The application is divided into three main columns: To Do, In Progress and Done.

The user can put a new task in To Do column, then he can grab it and put it to In Progress column when he wants to starts the tasks and finally he can grab it again to the Done column when he accoplish his task.

JavaScript handles user interactions and communicates with the API using HTTP requests.

### Example

```
┌─────────────┐  ┌─────────────┐  ┌─────────────┐
│    To Do    │  │ In Progress │  │    Done     │
├─────────────┤  ├─────────────┤  ├─────────────┤
│   Task 1    │  │   Task 3    │  │   Task 5    │
│   Task 2    │  │   Task 4    │  │             │
└─────────────┘  └─────────────┘  └─────────────┘
```

## Installation

Clone the repository:

```bash
git clone https://github.com/abdourhd/frontend-projects.git
```

Navigate into the project:

```bash
cd Project-3
```

Then open `index.html` in your browser.

No dependencies or installation are required.

## Author

**Abdou**

- GitHub: [abdourhd](https://github.com/abdourhd)

## License

This project is open-source.
