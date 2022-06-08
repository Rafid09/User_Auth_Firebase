# About the Project

- This is a simple user authention process using react.js and Firebase as backend which is developed by Google.
- User will sign up/register using email & password which will be saved in Firebase and later he may log in usig his credentials used before to register or sign up.
- If the user forgets his password he may reset it by giving his email address where further instructions will be sent to help the user reset his password.
- User credentials can be updated as well while the user is logged in to the system.

## Getting Started with the React App

To get started with the app, first you need a react project. Node.js is needed to be installed in the device. To create a react project you may use VSCode as an editor, select a workplace folder and type in the following command in the VSCode terminal to create a react project:

*npx create-react-app my-app*

Instead of "my-app" you may name your project according to your will.

## Setting up Firebase

Type in firebase console in Google and select Add project. Name your project and create one. After your project has been initialized you will be given some firebase credentials like api key, project id, app id, auth domain etc which will be necessary to use in the project for using and connecting firebase. You may look for them in project settings as well.

In the project directory, you need to run the following command to install and use firebase in your project:

*npm i firebase*

## Required dependencies

To use the React bootstap stylesheet and react router for the porject run the following commands in the VSCode terminal of your project directory:

- *npm i bootstrap react-bootstrap*
- *npm i react-router-dom*

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

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
