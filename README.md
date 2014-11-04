# cf-example-nodejs-famous

A barebones Node.js app using [Express 4](http://expressjs.com/) and [Famous](http://famo.us/).

## Deploying to Cloudfoundry

```
git clone https://github.com/Altoros/cf-example-nodejs-famous
cf push -p cf-example-nodejs-famous -b https://github.com/cloudfoundry/nodejs-buildpack cf-example-nodejs-famous
```
