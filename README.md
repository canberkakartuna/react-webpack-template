# React Webpack Starter

This is a React application created using webpack.

## Project Structure

```
my-react-app
├── src
│   ├── components
│   │   └── App.js
│   ├── index.js
│   └── index.html
├── dist
├── webpack
│   └── webpack.common.js
│   └── webpack.dev.js
│   └── webpack.prod.js
├── package.json
├── .babelrc
└── README.md
```

## File Descriptions

- `src/components/App.js`: This file exports a React component `App` which represents the main component of the application.
- `src/index.js`: This file is the entry point of the application. It renders the `App` component into the DOM.
- `src/index.html`: This file is the HTML template for the application. It includes a div element with an id of "root" where the React app will be mounted.
- `dist/`: This directory will contain the bundled and optimized files generated by webpack.
- `webpack/`: This directory contains the webpack configuration files for development, production, and common settings.
- `webpack/webpack.common.js`: This file contains the common webpack configuration settings used in both development and production environments.
- `webpack/webpack.dev.js`: This file contains the webpack configuration settings for development.
- `webpack/webpack.prod.js`: This file contains the webpack configuration settings for production.
- `package.json`: This file is the configuration file for npm. It lists the dependencies and scripts for the project.
- `.babelrc`: This file is the configuration file for Babel. It specifies the presets and plugins to use for transpiling JSX and ES6 code.
- `README.md`: This file contains the documentation for the project.

## Getting Started

To run the project, follow these steps:

1. Install the dependencies listed in the `package.json` file by running the command `npm install`.
2. Build the project by running the command `npm run build`.
3. Open the `dist/index.html` file in your web browser.

That's it! You should now see the React application running in your browser.

## Development

During development, you can use the following commands:

- `npm run start`: Starts the development server and opens the application in your default browser. The application will automatically reload whenever you make changes to the source code.
- `npm run build`: Builds the project for production. The optimized files will be generated in the `dist/` directory.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
