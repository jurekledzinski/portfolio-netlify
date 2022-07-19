# ![WebApp](https://github.com/jurekledzinski/Portfolio/blob/media/images/Portfolio.jpg?raw=true)

# Portfolio

Landing page portfolio

### Features

- Animated svgs.
- Contact email form.
- Managment state with redux.
- Slider
- Smooth scroll
- Validation form with formik and yup

### Technologies

Build with:

- [ReactJS](https://reactjs.org/) - A JavaScript library for building user interfaces.
- [React router](https://reactrouter.com/) - Collection of navigational components.
- [Redux](https://redux.js.org/) - A Predictable State Container for JS Apps.
- [NodeJS](https://nodejs.org/en/) - JavaScript runtime built on Chrome's V8 JavaScript engine.
- [ExpressJS](https://expressjs.com/) - Fast, unopinionated, minimalist web framework for Node.js.
- [Mongoose](https://mongoosejs.com/) - Elegant MongoDB object modeling for Node.js.
- [Firebase](https://firebase.google.com/) - Platform developed by Google for creating mobile and web applications.
- [Scss](https://sass-lang.com/) - CSS extension language.
- [Webpack](https://webpack.js.org/) - bundle assets, style, scripts, images ...
- [Formik](https://formik.org/) - Library to help build and validate forms.
- [Nodemailer](https://nodemailer.com/about/) - is a module for Node.js applications to allow email sending.

### Installation

Application requires [Express](https://expressjs.com/) v4+ and [Webpack](https://webpack.js.org/) v5 to run.

Backend installation

```sh
clone respository or download files
create .env file in root folder
add in .env file:
ATLAS_URL= xxxx mongo atlas url xxxx
NODE_ENV=development
SESS_NAME=xxxx session name xxxx
SESS_SECRET=xxxx session secret xxxx
HOST_EMAIL=xxxx smtp host email xxxx
PORT_PROVIDER_EMAIL=xxxx port provider email xxxx
EMAIL_USER= xxxx shop email, from where is send confirmation xxxx
PASSWORD_USER= xxxx password generated by your email provider xxxx
EMAIL_SENDTO=xxxx where should come email from clients xxxx
npm install in root folder
```

Client installation

```sh
cd ./client
npm install in client folder
```

- In app.js file in root folder, in cors origin change to http://localhost:3000
- In package.json file in client folder, remove proxy.
- In client/src/helpers/request.js in axios.create --- add line: baseURL: "http://localhost:5000"

### Run application

Run backend server

```sh
npm run start_local - run locally
```

Run client server

```sh
cd ./client
npm run dev - run locally
```

#### See live

[Portfolio](...)

## License

MIT © [Jurek Ledziński](https://github.com/jurekledzinski)
