This project is Garage store ReactJS application (FE part of the NodeJS in AWS Cloud mentoring)

## Available Scripts

In the project directory, you can run:  
You can use NPM instead of YARN (Up to you)  

### `npm run start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm run test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run deploy:s3`

Runs deploy built application (from /build folder) to the configured s3 bucket with using serverless-finch plugin.
Configuration of the serverless-finch plugin and s3 bucket see in serverless.yml file

### `npm run build:deploy`

It is the combination of `npm run build` and `npm run deploy:s3` scripts

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
