# Task - Todo Management App

iTask is a simple and efficient task management application built using React and Tailwind CSS. It allows users to add, edit, delete, and mark tasks as completed while persisting data using local storage.

## Features

- **Add Todos**: Users can add new tasks to their list.
- **Edit Todos**: Modify an existing task.
- **Delete Todos**: Remove tasks from the list.
- **Mark as Completed**: Check off completed tasks.
- **Show/Hide Completed Tasks**: Toggle visibility of finished tasks.
- **Local Storage Support**: Persist tasks even after refreshing the page.

## Technologies Used

- React.js
- Tailwind CSS
- UUID (for unique task IDs)
- React Icons (for edit and delete icons)
- Local Storage (for saving tasks)

## Installation and Setup

1. **Clone the repository**:
   ```sh
   git clone https://github.com/suryanag9099/iTask.git
   cd iTask
   ```

2. **Install dependencies**:
   ```sh
   npm install
   ```

3. **Start the development server**:
   ```sh
   npm start
   ```

   The app will be available at `http://localhost:3000/`.

## File Structure

```
/src
│── components
│   ├── Navbar.js   # Navigation bar component
│── App.js          # Main application logic
│── index.js        # Entry point for React app
│── styles.css      # Custom styling (Tailwind included)
│── README.md       # Project documentation
```

## How to Use

1. Enter a task in the input field and click **Save** to add it.
2. Click the **Edit** button (✏️) to modify an existing task.
3. Click the **Delete** button (🗑️) to remove a task.
4. Check/uncheck the checkbox to mark a task as completed.
5. Use the "Show Finished" checkbox to toggle completed tasks.

## Contributing

Feel free to submit issues or pull requests to improve the project!

## License

This project is licensed under the MIT License.

