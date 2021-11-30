# Getting started with NFX React Web Boilerplate

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

#### Few other environment run scripts

| Run Script                                           | Description                 |
| ---------------------------------------------------- | --------------------------- |
| <span style="color:brown">**npm start:qa**</span>    | Runs in QA environment      |
| <span style="color:brown">**npm start:stage**</span> | Runs in Staging environment |

## About the boilerplace

This boilerplate is created in the interest of developers to make the basic development process easy. This template has various architectural and environment setups.

### Environments

| Run Script | Env file |
| ---------- | -------- |
| dev        | .dev     |
| qa         | .qa      |
| staging    | .staging |
| prod       | .prod    |

# Structure

```
📦Project
 ┣ 📂.vscode
 ┃ ┗ 📜settings.json
 ┣ 📂jest
 ┃ ┗ 📜setup.js
 ┣ 📂public
 ┃ ┣ 📜favicon.ico
 ┃ ┣ 📜index.html
 ┃ ┣ 📜logo192.png
 ┃ ┣ 📜logo512.png
 ┃ ┣ 📜manifest.json
 ┃ ┗ 📜robots.txt
 ┣ 📂src
 ┃ ┣ 📂auth
 ┃ ┃ ┗ 📜AuthContext.js
 ┃ ┣ 📂components
 ┃ ┃ ┣ 📂Loader
 ┃ ┃ ┃ ┗ 📜AppLoader.js
 ┃ ┃ ┗ 📂Typography
 ┃ ┃ ┃ ┗ 📜index.js
 ┃ ┣ 📂helpers
 ┃ ┃ ┣ 📂__tests__
 ┃ ┃ ┃ ┣ 📜functionTests.js
 ┃ ┃ ┃ ┗ 📜sorterTests.js
 ┃ ┃ ┣ 📜functions.js
 ┃ ┃ ┣ 📜index.js
 ┃ ┃ ┣ 📜package.json
 ┃ ┃ ┗ 📜sorters.js
 ┃ ┣ 📂hoc
 ┃ ┃ ┣ 📜AuthWrapper.js
 ┃ ┃ ┗ 📜PublicWrapper.js
 ┃ ┣ 📂layout
 ┃ ┃ ┣ 📜privateLayout.js
 ┃ ┃ ┗ 📜publicLayout.js
 ┃ ┣ 📂network
 ┃ ┃ ┣ 📂core
 ┃ ┃ ┃ ┣ 📜apiModel.js
 ┃ ┃ ┃ ┣ 📜endpoints.js
 ┃ ┃ ┃ ┣ 📜httpMethods.js
 ┃ ┃ ┃ ┣ 📜index.js
 ┃ ┃ ┃ ┣ 📜networkManager.js
 ┃ ┃ ┃ ┣ 📜responseParser.js
 ┃ ┃ ┃ ┣ 📜serverConfig.js
 ┃ ┃ ┃ ┗ 📜tokenRefresher.js
 ┃ ┃ ┣ 📜authService.js
 ┃ ┃ ┣ 📜index.js
 ┃ ┃ ┗ 📜package.json
 ┃ ┣ 📂pages
 ┃ ┃ ┣ 📂common
 ┃ ┃ ┣ 📂private
 ┃ ┃ ┃ ┣ 📂dashboard
 ┃ ┃ ┃ ┃ ┗ 📜index.js
 ┃ ┃ ┃ ┗ 📂settings
 ┃ ┃ ┃ ┃ ┗ 📜index.js
 ┃ ┃ ┣ 📂public
 ┃ ┃ ┃ ┣ 📂login
 ┃ ┃ ┃ ┃ ┣ 📂__tests__
 ┃ ┃ ┃ ┃ ┃ ┗ 📜loginTests.js
 ┃ ┃ ┃ ┃ ┗ 📜index.js
 ┃ ┃ ┃ ┗ 📂signup
 ┃ ┃ ┃ ┃ ┗ 📜index.js
 ┃ ┃ ┗ 📜Error404.js
 ┃ ┣ 📂redux
 ┃ ┃ ┣ 📂actions
 ┃ ┃ ┃ ┗ 📜appActions.js
 ┃ ┃ ┣ 📂dispatchers
 ┃ ┃ ┃ ┗ 📜appDispatcher.js
 ┃ ┃ ┣ 📂reducers
 ┃ ┃ ┃ ┗ 📜appReducer.js
 ┃ ┃ ┣ 📜index.js
 ┃ ┃ ┣ 📜package.json
 ┃ ┃ ┗ 📜store.js
 ┃ ┣ 📂router
 ┃ ┃ ┣ 📂routes
 ┃ ┃ ┃ ┣ 📜index.js
 ┃ ┃ ┃ ┣ 📜privateRoutes.js
 ┃ ┃ ┃ ┗ 📜publicRoutes.js
 ┃ ┃ ┣ 📜index.js
 ┃ ┃ ┗ 📜package.json
 ┃ ┣ 📂themes
 ┃ ┃ ┗ 📜defaultTheme.js
 ┃ ┣ 📜App.css
 ┃ ┣ 📜App.js
 ┃ ┣ 📜App.test.js
 ┃ ┣ 📜index.css
 ┃ ┣ 📜index.js
 ┃ ┣ 📜logo.svg
 ┃ ┣ 📜reportWebVitals.js
 ┃ ┗ 📜setupTests.js
 ┣ 📜.env
 ┣ 📜.env.dev
 ┣ 📜.env.prod
 ┣ 📜.env.qa
 ┣ 📜.env.staging
 ┣ 📜.eslintrc.js
 ┣ 📜.gitignore
 ┣ 📜.prettierrc
 ┣ 📜README.md
 ┣ 📜babel.config.js
 ┣ 📜config-overrides.js
 ┣ 📜jest.config.js
 ┣ 📜jsconfig.json
 ┣ 📜package-lock.json
 ┗ 📜package.json
```

## Some basic instructions

- All the url facing components should be placed in `pages` directory
- All the sharable components should be placed inside `components` directory
- Themes can be managed in `themes` directory
- This boilerplate is already set with Material-UI v5. You need not to update anything.
- This boilerplate is also set with Redux and authentication flow. So all the routing can be managed accordingly.
- All the private routes should be declared in `router/routes/privateRoutes.js` and all the public routes should be declared in `router/routes/privateRoutes.js` file.
- If you need to update theme and colors, please make those changes in `src/themes/defaultTheme.js` file or create a new one in the same directory.
- Theme should be loaded in `src/App.js` `createTheme()` function

## Imports

All the imports in this project are being managed by [react-app-rewired](https://www.npmjs.com/package/react-app-rewired). The config file for this plugin is `config-overrides.js` located at the root of the project.

### How to import modules

To import modules, just place `@` before the name of directory followed by the file name.
For example, If I want to import `AppLoader` from `src/components/Loader/AppLoader.js` then the import would look like

```js
import AppLoader from "@components/Loader/AppLoader";
```

You need not to write long import paths for most of the times.

**If you need to add any other directory in this import, add the path to `config-overrides.js` and in `jsconfig.json`**

## Some other important points

- This boilerplate is set with `redux-persist` and you need not set values explicitly in localStorage.
- All you need to do is dispatch the action to redux and set/read the values from redux.
- All the API calls will be done by `NetworkManage.js` using fetch API.

### Network call Example

#### Step 1

Setup the API url in `.env.dev` or related environment file

```bash
REACT_APP_API_URL=https://dev.example.com
```

#### Step 2

Open `src/network/core/endpoints.js` and place the endpoint for the call. For example, If we want to add `/login` endpoint, then we will add like this

```js
export const API = {
  AUTH: {
    LOGIN: new Endpoint("/auth", HTTP_METHODS.POST)
  }
};
```

Though the call is related to authentication, we'll put this under the `AUTH` property. \
The second parameter in the Endpoint Class is `HTTP` method. This will be one of `HTTP_METHODS.`

- POST
- GET
- PUT
- DEL
- PATCH

#### Step 3

Now create a new service file in `network/` directory. We'll create `authService.js` file for our case.

```js
// Sample service to make network call

import { API, NetworkManager } from "./core";

export class AuthService {
  static async loginByEmail(payload) {
    const instance = new NetworkManager(API.AUTH.LOGIN, payload);
    return await instance.httpRequest(false);
  }
}
```

First you need to create a new instance of the `NetworkManager` by passing the Endpoint and the body parameter.

### `npm run test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.
