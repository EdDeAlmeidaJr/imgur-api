## imgur-api

### Author: Ed de Almeida (edvaldoajunior@gmail.com)

API to help using IMGUR service to store images.

### Registering your app

Before using **imgur-api**, please:

- Register your application at [Register app - Imgur](https://api.imgur.com/oauth2/addclient).
- Install (if you don't have) the NPM module **dotenv**: [dotenv at NPM](https://www.npmjs.com/package/dotenv).
- Start dotenv in you application's initial file using **require('dotenv').config()**.
- Create (if you don't have) a .env file at the root folder of your app with **npm install dotenv --save**.
- Add two lines to your .env file:
  IMGUR_KEY=<your-imgur-key>
  IMGUR_SECRET=<your-imgur-secret>


