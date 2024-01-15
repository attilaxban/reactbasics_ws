# React basics workshop

In this section, we will be implementing a single-page application in React to display our favorite programming languages. Users can vote for individual programming languages, and the total number of votes received for each language can be viewed on their respective pages.
**These implementations will focus on using states to display various pages and facilitate parent-child data communication.**

## Install dependencies

### Install dependencies for Express server
```bash
cd backend
npm install
```

### Install dependencies for React
```bash
cd frontend
npm install
```

## Launch the backend server
```bash
cd backend
npm run devStart
```

## Launch the frontend
```bash
cd frontend
npm run dev
```

## TASKS
If you have successfully completed all the above points, the page will load without errors but with empty content. Next, we will work on getting the functionality of the page up and running. To do this, you need to go through the listed tasks. In the `./frontend/src` directory, find a file with a comment matching the task point, for example, `TASK 1` and implement the requested functionality.

### TASK 1: State implementation
Create a state named `page` that tracks the current state of the page!

### TASK 2: Navbar implementation
Render the `Layout` component in a way that it always appears on the screen regardless of the page!

### TASK 3-6: Switching between different pages
Implement the following: upon clicking any of the buttons within the `Layout` component, update the `page` state in the `App` component to contain the corresponding string. These strings can be: `main`, `about`, `demo`, `language-creator`, `error`!

### TASK 7: Rendering different pages
Examine the state of the `page` state and render the corresponding component. You can find the names of the components after the import statements at the top of the file!

### TASK 8: Programming languages details
Find a way to update the `page` state with the provided structure so that we can render the details of a specific programming language!

### TASK 9: Rendering details of a programming language
Based on the previously updated `page` state, render the details of the respective programming language!