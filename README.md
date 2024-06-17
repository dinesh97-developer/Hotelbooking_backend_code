

## Installing Packages

```sh
# PACKAGES FOR APPLICATION USAGES
npm install express             // web framework for node.js
npm install serve-favicon       // api router favicon sets
npm install mongoose            // mongo-db database schema-based solution to model your application data
npm install dotenv              // environment variables
npm install cors                // allow cors policy
npm install winston             // node app logger for just about everything
npm install helmet              // express apps by setting various HTTP headers
npm install morgan              // HTTP request logger middleware
npm install app-root-path       // simply access the app root path
npm install multer              // node.js 'multipart/form-data' file upload
npm install express-rate-limit  // basic rate-limiting middleware for express.js

# PACKAGES FOR USER AUTHENTICATION
npm install bcryptjs            // password encryption
npm install jsonwebtoken        // generate jwt token
npm install validator           // email and phone number validator
npm install crypto              // data encryption and decryption
npm install cookie-parser       // parse HTTP request cookies
npm install body-parser         // node.js body parsing middleware
npm install @sendgrid/mail      // send emails using sendgrid service
```

## Setup Development Environment

### 1. Vs-Code Extensions

Install the below extensions:

- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

### 2. Install Global Dependencies

```sh
npm install -g npm@latest
npm install -g nodemon@latest
npx install -g win-node-env@latest
npx install -g jest@latest
```

### 3. Install Dev Dependencies

```sh
npm install -D eslint
npm init @eslint/config
npx install-peerdeps --dev eslint-config-airbnb-base
npm install -D eslint-plugin-node eslint-config-prettier eslint-plugin-prettier
```

### 4. Install Dev Dependencies for App Testing

```sh
npm install -D jest supertest superagent
npm install -D @babel/core @babel/preset-env babel-jest
jest --init // initialize jest for app testing
```


