This repository contains changes for the user to make an interactive personal dashboard for task management.
The user wants to create a web based, trame powered tool that keeps tasks in a CSV format.
The silent features are
1. Easy way for user to create tasks -- simply by clicking a button.
    -- The user is asked for Task title, task notes, and the expected deadline.
    -- The task is represented using a card but in form of a gantt chart, the user can drag drop tasks based on their status.
    -- The status can be pending, in-progress, completed -- once completed the task is only archived.
2. A Dashboard reporting on the progress -- on time, late, etc.
3. Each tasks when clicked should expand displaying the notes of it, and the user can then edit the notes.
  -- the edit mode should be plain text markdown
  -- the display mode should be rendered markdown

The technology stack right now is python, trame, and it's associated libraries.

Follow proper software engineering practices, and interactively prototype with user before integrating in main app any UI piece.
