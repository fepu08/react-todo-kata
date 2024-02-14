# To-Do kata

Create a simple to-do app with CRUD functionalities and use hooks like `useState`, `useEffect`, `useContext`, `useReducer`:

- use json-server (pre-installed), and create axios calls to these endpoints (`/todo`, `/todo:id`)
- for creating a to-do
	- use a separate route
  - use a form
  - does not allow user to make the same task twice
  - task `done` attribute is false by default
- list them under the form
  - task description
  - show done attribute as checkbox
    - if checkbox is checked pull through description
