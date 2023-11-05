# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

############### TASKS DETAILS ##################
In this task, we will transform the work you did using pure JS into react project.
We will start by building the first page then second page.

I will start by adding the reading materials this time because you do not have experience in react, and its important to learn the CONCEPT of react and why it was created.

Reading Materials:
Thinking in react --> https://react.dev/learn/thinking-in-react
Describing the UI --> https://react.dev/learn/describing-the-ui (first 5 topics are important)
State: A Component's Memory --> https://react.dev/learn/state-a-components-memory
states updates --> https://react.dev/learn/updating-objects-in-state
input states --> https://react.dev/learn/reacting-to-input-with-state
sharing states --> https://react.dev/learn/sharing-state-between-components
HOOKS (Focus on useState, useEffect and useContext) --> https://react.dev/reference/react
life cycles -->https://react.dev/learn/lifecycle-of-reactive-effects

While reading I want you to start practicing what you are reading therefore, start creating the first page which is the login page.
React Components:
1- input field --> this input takes props value such as type, placeholder.
2- button --> thinking of our project, we only have one button thus it wont take any props

for redirecting please use react router https://reactrouter.com/en/main

###################################################################################

TODO List Task:
for this task, you will be using localStorage to keep track of your todo list array. you will start with an empty list. the todo item will be an object consist of the following:
id:string (make it a random numeric string),
task:string,
completed : boolean,
createdAt: Date

(images will be shared with you on teams)

1- start by creating the nav bar which has the below tabs:
All: will show all the TODO items active and completed and their perspective UI
Active: will only show the TODO items that are still in the active state (not completed)
Completed: will only show the TODO items that are completed  currently, do not do anything but think about creating the nav bar and how to switch between the tabs and the logic inside each tab.

2- We will create the textfield component and the Add button:

- This component should be present on all 3 tabs and it should be ONE component only.
- If the user clicked the button and the textfield is empty, show an error message and do not add change the TODO list array

We will complete the rest once the above is done.
