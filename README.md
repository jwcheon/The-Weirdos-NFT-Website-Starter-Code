### Keeping track
✅ : Good stuff reminder
💡 : Learned new tricks
😢 : Didn't quite get yet

## 1. Basic starter settings
- Wrap App in index.js with BrowserRouter (react-router-dom)
- Import 'normalize.css' into index.js to remove default css
- Create GlobalStyles.js for font & margin defaults > pass in as a component in App.js
- ✅ Themes.js for light/dark mode > ThemeProvider with styled-components in App.js
- Create basic sections & footer, navigation > load them as components in App.js

## 2. Navigation
- Section > Navbar > Menu > MenuItem
- Create Logo.js with the prepared font + Link
- 💡 'list-style: none' on ul to remove dot from li
- 💡 Use '&::after' on MenuItem to create a underline transition on hover(&:hover::after)
- ✅ Create Button.js component and pass in attrs 'text' & 'link' for reusability
- 😢 (didn't exactly understand how the button ring transition trick works...)

## 3. Home Section
- 💡 Give 'min-height' to Home Section with calc(100vh - navSection)
- 💡 Section Layout Pattern (Section > Container): 1) Section: width 100vw & min-height/height of 100vh / 2) Container: ex. width 75% & min-height 80vh & margin 0 auto
- Include the round cycling loop component with position absolute.
- Create inner circle with a span & hexcode, w/ a positioning trick: 😢 top: 50%; left: 50%; transform: translate(-50%, -50%);




# How to Create NFT Collection Landing Page in React JS

This repository contains starter code for NFT Collection Website in ReactJS. <br />

View Demo👇: <br />
https://the-weirdos.netlify.app/ <br />

If you want to learn how to create it please follow below tutorial👇: <br />

https://youtu.be/edr2o59Twrs <br />

### Images of The NFT Collection Website:
![HOME](https://github.com/codebucks27/The-Weirdos-NFT-Website-Starter-Code/blob/main/Home%20-%20Desktop.png)
![ABOUT](https://github.com/codebucks27/The-Weirdos-NFT-Website-Starter-Code/blob/main/Home-2%20-%20Desktop.png)
![HOME](https://github.com/codebucks27/The-Weirdos-NFT-Website-Starter-Code/blob/main/Home-1%20-%20Mobile.png)
![MENU](https://github.com/codebucks27/The-Weirdos-NFT-Website-Starter-Code/blob/main/Home-2-%20Mobile.png)


### Resources Used in This Project

Character Figures: https://bigheads.io/ <br />
Fonts: https://fontsource.org/ <br />
Svg Icons From: https://icons8.com & https://freesvg.org/   <br />

### External Libraries used in this project: 

[styled-components](https://styled-components.com/docs/advanced) <br />
[GSAP](https://greensock.com/gsap/) <br />
[type-writer effect](https://www.npmjs.com/package/typewriter-effect) <br />
[react-confetti](https://www.npmjs.com/package/react-confetti) <br />
[react-use](https://www.npmjs.com/package/react-use) <br />

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
