# Summary
A dummy node.js project

Framework: express
View: ejs
Database: MongoDB
Session/Cache: Redis
Test framework: Jest
Deployment: K8S

## Installation
npm install

## Usage
docker build -t node-app .
docker run -p 3000:3000 --name node-app -d node-app
docker stop node-app
docker rm node-app

## Structure
- dist
- node_modules
- public
- src
- views
package.json
tsconfig.json

## License
[MIT](https://choosealicense.com/licenses/mit/)