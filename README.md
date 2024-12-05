# React ToDo App

Implemented a simple [TODO app](https://mate-academy.github.io/react_todo-app/) that functions as described below.

![todoapp](./description/todoapp.gif)

- Show only a field to create a new todo if there are no todos yet.
- Use React Context to manage todos.
- Each todo should have an `id` (you can use `+new Date()`), a `title`, and a `completed` status (`false` by default).
- Save `todos` to `localStorage` using `JSON.stringify` after each change.
- Display the number of not completed todos in `TodoApp`.
- Implement filtering by status (`All`/`Active`/`Completed`).
- Add the ability to delete a todo using the `x` button.
- Implement the `clearCompleted` button (disabled if there are no completed todos).
- Implement individual todo status toggling.
- Implement the `toggleAll` checkbox (checked only when all todos are completed).
- Enable inline editing for the `TodoItem`:
    - Double-clicking on the todo title shows a text field instead of the title and `deleteButton`.
    - Form submission saves changes (press `Enter` to save).
    - Trim the saved text.
    - Delete the todo if the title is empty.
    - Save changes `onBlur`.
    - Pressing `Escape` cancels editing (use `onKeyUp` and check if `event.key === 'Escape'`).

![todoedit](./description/edittodo.gif)


## Demo Links

- [DEMO LINK](https://AndriiZakharenko.github.io/react_todo-app/)
