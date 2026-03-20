Todo App is a functional task management tool designed to help users organize, track, and control their daily activities. Built as a Single Page Application (SPA), it focuses on a seamless user experience and real-time synchronization with a server.

Core Features:
- Task Management: Quickly add new tasks, edit titles (inline editing), or remove outdated items.

- Progress Tracking: Mark tasks as completed with a visual "strike-through" effect to keep track of progress.

- Bulk Actions: A "Toggle All" feature to change the status of all tasks at once and a "Clear Completed" button for mass deletion.

- Smart Filtering: Easily sort tasks into three categories: All, Active, and Completed.

- Dynamic UX: Includes auto-focusing on the input field, individual loading indicators (spinners) for each task, and a notification system for API error handling.

Experiance the live website:

Technical Highlights:
The application is built using a modern stack:

- React Hooks: Leveraging useState, useEffect, useMemo, and useCallback for efficient rendering and state logic.

- TypeScript: Ensuring robust data typing and reducing runtime errors.

- REST API Integration: Full synchronization with a backend to persist task data across sessions.


1. Clone the repository:
git clone https://github.com/your-username/project-name.git
cd project-name

2. Install dependencies:
npm install
# or
yarn install

3.Run the project locally:
npm start
# or
yarn start
