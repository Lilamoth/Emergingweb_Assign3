# Task Manager Application

This project is a simple Task Manager application built with React. It allows users to add, update, delete, and toggle tasks. Additionally, it supports dark mode and task filtering.

## Features

- **Add Task**: Users can add new tasks with a title and description.
- **Update Task**: Users can update existing tasks.
- **Delete Task**: Users can delete tasks.
- **Toggle Task**: Users can mark tasks as completed or incomplete.
- **Dark Mode**: Users can toggle between light and dark modes.
- **Task Filtering**: Users can filter tasks by all, completed, or incomplete.

## Components

### `App.js`

- **ThemeContext**: A context to manage the dark mode state.
- **taskReducer**: A reducer function to handle task-related actions.
- **TaskManagerApp**: The main component that manages tasks and filtering logic.
- **App**: The root component that provides the dark mode context.

## Hooks Used

- **useReducer**: To manage the state of tasks.
- **useState**: To manage form inputs and filter state.
- **useEffect**: To save tasks to localStorage and focus the title input on component mount.
- **useRef**: To reference the title input element.
- **useMemo**: To memoize the filtered tasks.
- **useCallback**: To memoize the task operations (add, toggle, delete).

## Local Storage

- Tasks and dark mode state are saved to localStorage to persist data across page reloads.

## How to Run

1. Clone the repository.
2. Navigate to the project directory.
3. Install dependencies using `npm install`.
4. Start the development server using `npm start`.

## File Structure

```
src/
  ├── App.js
  ├── App.css
  └── index.js
```

## Future Improvements

- Add task editing functionality.
- Improve UI/UX with better styling.
- Add user authentication to save tasks for individual users.

## License

This project is licensed under the MIT License.
