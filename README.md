<!-- This section refers to the answer to my assignment question 2 to 6 -->

## Quesion 2

- List five significant features of React

1. Virtual DOM: React uses a virtual DOM to render user interfaces, which allows it to update only the parts of the UI that have changed, rather than having to reload the entire page. This makes React very fast and efficient.

2. Component-based architecture: React is built around the concept of reusable components, which are independent, modular pieces of code that can be used to build complex user interfaces. This makes it easy to create and maintain large applications, as well as to reuse code across different projects.

3. JSX: JSX is a syntax extension for JavaScript that allows developers to write HTML-like code within their JavaScript files. This makes it easy to create complex user interfaces without having to write a lot of boilerplate code.

4. Unidirectional data flow: React follows a unidirectional data flow architecture, which means that data flows in one direction, from the parent component down to its children. This makes it easier to reason about data flow and makes debugging easier.

5. React Native: React Native is a mobile app development framework that allows developers to build native mobile apps using React. This means that developers can use their existing React skills to build mobile apps for both iOS and Android, which makes it easier to create cross-platform apps.

## Quesion 3

- List five major advantages of React

1. Reusable Components: React's component-based architecture allows developers to build reusable UI components, which can be used across different projects. This can save development time, reduce code duplication, and make code maintenance easier.

2. Virtual DOM: React's Virtual DOM is a lightweight representation of the actual DOM, which allows React to update only the parts of the UI that have changed, rather than having to reload the entire page. This makes React faster and more efficient than other UI libraries or frameworks.

3. Performance: React's performance is one of its major advantages. Thanks to its Virtual DOM, React is able to render UI changes quickly, which makes it suitable for building large-scale applications that require frequent updates.

4. Community and Ecosystem: React has a large and active community, with many developers contributing to its ecosystem of tools and libraries. This makes it easier for developers to find solutions to problems, as well as to share code and collaborate on projects.

5. Cross-Platform Development: With React Native, developers can use their existing React skills to build mobile apps for both iOS and Android. This allows for easier cross-platform development and reduces the need for specialized knowledge in each platform.

## Quesion 4

- What is the name of the Software Engineer that created React? Also, which company owns React?

* The software engineer who created React is Jordan Walke. React was initially developed by Facebook, and it is now owned and maintained by Facebook and a community of individual developers and companies. Facebook open-sourced React in 2013, allowing developers around the world to use and contribute to its development.

## Quesion 5

- What are the notable differences between HTML & JSX? Give at least 3 of them

1. Syntax: The syntax for HTML and JSX are different. HTML uses angle brackets to define elements and attributes, while JSX uses similar syntax but with curly braces and a special syntax for defining attributes. For example, in HTML you might define an image with the following code: <img src="image.jpg" alt="An image">. In JSX, you would define the same image like this: <img src={"image.jpg"} alt={"An image"} />.

2. Components: JSX allows you to define and use components, which are reusable pieces of code that can be composed together to build complex interfaces. Components in JSX are defined using JavaScript functions or classes, and they can receive and return data. HTML does not have a concept of components, so you cannot reuse code in the same way.

3. Expressiveness: JSX is more expressive than HTML. This is because JSX is based on JavaScript, which is a more expressive language than HTML. JSX allows you to use expressions and statements to define elements and attributes, which makes it easier to create dynamic and interactive interfaces. For example, in JSX, you can use expressions like {name} to insert the value of a variable into an element or attribute, while in HTML you would need to use string concatenation or a templating language to achieve the same result.

## Quesion 6

- Why can’t browsers read JSX?

* Browsers cannot read JSX directly because JSX is not a standard web language. Instead, it is a syntax extension of JavaScript. Browsers can only read and interpret HTML, CSS, and JavaScript.

JSX needs to be compiled into JavaScript before it can be understood by a browser. This is typically done using a tool like Babel, which transpiles JSX into regular JavaScript that can be understood by browsers.

When you use a tool like Babel to transpile your JSX code, the resulting JavaScript code will create the necessary HTML elements and manipulate the DOM just like any other JavaScript code. So, even though browsers cannot read JSX directly, they can still render JSX-generated content as HTML elements and manipulate them using JavaScript

<!-- Below here is how to get started with react -->

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
