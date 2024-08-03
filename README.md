To add the descriptions of your `Home.jsx`, `Login.jsx`, `EmailReply.jsx`, and `Header.jsx` components to your GitHub README file, you can structure it in a clear and organized way. Here’s a sample README section that includes details about each component:

---

## Project Overview

This project is a web application with a focus on user authentication and email management. Below is a brief overview of the key components and their functionalities.

### `Home.jsx`

The `Home.jsx` file structures the main home page of the application. It integrates various UI components and manages their layout and state.

- **Imports and State Management:** Imports components like `Header`, `Navbar`, `Inbox`, `Message`, and `LeadDetails`. Uses `useState` to control the visibility of the inbox modal.
- **Page Layout:** Utilizes a `div` with `relative` class for proper positioning. Uses flexbox for aligning `Navbar`, `Inbox`, `Message`, and `LeadDetails` components.
- **Component Functionality:** Configures `Navbar` to manage `inboxModal` state, influencing the display of `Inbox` and `Message` components.

### `Login.jsx`

The `Login.jsx` file handles user authentication, focusing on Google Sign-In with a clean and responsive interface.

- **State and Navigation:** Manages login/signup modes using `useState` and handles routing with `useNavigate`.
- **Google Authentication:** On load, checks for a token in URL parameters, stores it in localStorage, and redirects the user if necessary.
- **UI Design:** Features a minimalist black-themed design with a centered login/signup form, gradient backgrounds, and responsive styling.

### `EmailReply.jsx`

The `EmailReply.jsx` component allows users to compose and send email replies within the application.

- **State Management:** Uses `useState` to handle input fields for "To", "From", "Subject", and the message body.
- **UI Structure:** Renders a modal with fields for composing emails and includes buttons for sending, adding variables, and previewing.
- **Styling:** Styled with Tailwind CSS to match the dark theme, using classes like `bg-[#141517]` and `text-white`.

### `Header.jsx`

The `Header.jsx` component manages the application's header, including theme toggling and workspace display.

- **Theme Management:** Manages light/dark theme state with `useState` and `useEffect`. Applies theme changes and persists them in localStorage.
- **UI Layout:** Displays the application’s name and workspace information. Integrates a `ThemeToggle` component for switching themes.
- **Styling:** Features a dark background (`bg-[#1F1F1F]`), border, and inset shadow for a sleek appearance.

---

Feel free to adjust the content to better fit your project's specifics or to add any additional sections as needed.




# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

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

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

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
