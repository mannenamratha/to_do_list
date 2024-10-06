

# To-Do App

A basic web-based To-Do application where users can add, edit, and delete tasks. The app also allows users to mark tasks as completed and persists the data using `localStorage` to keep tasks between browser sessions.

## Features

- **Add a new task**: Users can input new tasks into the text field and click the "Add" button or press the "Enter" key to add them to the list.
- **Mark tasks as complete**: Users can mark tasks as completed using a checkbox, which will strike through the text.
- **Edit tasks**: Users can click on a task to edit it in-line.
- **Delete all tasks**: Users can remove all tasks using the "Delete All" button.
- **Task persistence**: The app stores tasks in the browser's `localStorage` so that the list is retained after page refresh or reopening.
- **Item counter**: The app displays the total number of tasks.

## Folder Structure

```
├── index.html    # The HTML file for the To-Do app
├── style.css     # The CSS file for styling the To-Do app
└── script.js     # The JavaScript file containing app logic
```

## How to Run the App

1. Clone the repository or download the files.
2. Ensure that `index.html`, `style.css`, and `script.js` are in the same directory.
3. Open `index.html` in a web browser.
4. You can now interact with the app!

## Files Breakdown

- **HTML (`index.html`)**:
  - Defines the structure of the To-Do app.
  - Includes an input field for tasks, a list for displaying tasks, and buttons for adding and deleting tasks.

- **CSS (`style.css`)**:
  - Provides styling to the elements, such as buttons, input fields, and the task list.
  - Includes scrollbar customization for a better user experience.
  
- **JavaScript (`script.js`)**:
  - Handles the core functionality, such as adding, editing, deleting, and marking tasks as completed.
  - Utilizes `localStorage` to persist tasks.

## How It Works

1. **Adding a Task**:
   - When the user inputs a task and clicks "Add" or presses "Enter", the task is added to the `todo` array and displayed on the screen.
   - The task is saved to `localStorage`.

2. **Displaying Tasks**:
   - On page load or when a task is added, the tasks from the `todo` array are rendered in the task list.

3. **Editing a Task**:
   - Clicking on a task allows users to edit its text. Once they click outside the text field, the task is updated and saved.

4. **Marking Tasks as Complete**:
   - Users can mark tasks as complete using the checkbox. The text is struck through, and the task is marked as disabled.

5. **Deleting All Tasks**:
   - Clicking the "Delete All" button clears all tasks from the `todo` array and `localStorage`.

## Future Improvements

- Add categories for tasks (e.g., Work, Personal).
- Allow the user to set priorities for tasks.
- Implement due dates and reminders.
- Add sorting and filtering options for tasks.

## Technologies Used

- **HTML**: For structuring the web page.
- **CSS**: For styling the app and creating a responsive, modern UI.
- **JavaScript**: For implementing app logic, manipulating the DOM, and handling `localStorage`.

