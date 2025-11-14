# elevate-task-web-devlopment-2

# To-Do List Web App - Web Development Internship Task 2

This repository contains the solution for Task 2 of the Web Development Internship from Elevate Labs. [cite_start]The objective is to build a dynamic, front-end-only To-Do List web application using HTML, CSS, and **Vanilla JavaScript**[cite: 5].

## 🚀 Project Objective

[cite_start]The goal is to create a functional To-Do list where a user can dynamically add tasks, mark tasks as complete, and remove tasks from the list[cite: 6]. [cite_start]All operations must update the UI instantly without a page reload[cite: 17, 19].

## ✨ Features

* **Add Tasks:** Users can type a task into the input field and press "Add" or hit "Enter" to add it to the list.
* [cite_start]**Remove Tasks:** Each task has a "remove" button that, when clicked, instantly deletes the task from the list[cite: 15].
* [cite_start]**Complete Tasks:** Users can click a "complete" button or the task text itself to toggle a "completed" state[cite: 14], which is visually marked with a line-through.
* **Input Validation:** Empty or whitespace-only tasks are not added.
* **Fully Responsive:** The app has a clean, modern, and responsive design that works on all screen sizes.

## 🛠️ Technologies Used

* **HTML5:** Structured with semantic HTML.
* **CSS3:** Styled with Flexbox for a modern layout, custom fonts (Google Fonts), and icons (Font Awesome).
* [cite_start]**Vanilla JavaScript (ES6+):** Used for all DOM manipulation and event handling[cite: 31].

## 💡 Key Concepts Implemented

This project was a practical exercise in core JavaScript concepts:
* [cite_start]**DOM Manipulation:** Dynamically creating (`createElement`), appending (`appendChild`), and removing (`remove`) elements.
* [cite_start]**Event Handling:** Using `addEventListener` to capture user actions like 'submit' and 'click'.
* **Event Delegation:** Using a single event listener on the parent `<ul>` to efficiently manage clicks on all child tasks (for "complete" and "remove"). This is a more performant approach than adding a listener to every single task.
* [cite_start]**CSS Class Toggling:** Using `element.classList.toggle()` to dynamically change the appearance of completed tasks[cite: 14].

## 🖥️ How to View

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    ```
2.  **Open the file:**
    Navigate to the project folder and open the `index.html` file in your browser (using the "Live Server" extension in VS Code is recommended).
