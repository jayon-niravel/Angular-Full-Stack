# Angular Full Stack 
## Prerequisites
1. Install [Node.js](https://nodejs.org) and [MongoDB](https://www.mongodb.com)
2. Install Angular CLI: `npm i -g @angular/cli`
3. From project root folder install all the dependencies: `npm i`

## Run
### Development mode with files watching
`npm run dev`: [concurrently](https://github.com/kimmobrunfeldt/concurrently) execute MongoDB, Angular build, TypeScript compiler and Express server.

A window will automatically open at [localhost:4200](http://localhost:4200). Angular and Express files are being watched. Any change automatically creates a new bundle, restart Express server and reload your browser.

### Production mode
`npm run prod`: run the project with a production bundle listening at [localhost:3000](http://localhost:3000) 

### Manual mode
1. Build frontend: `npm run builddev` for dev or `npm run build` for prod
2. Build backend: `npm run predev`
3. Run MongoDB: `mongod`
4. Run the app: `npm start`
