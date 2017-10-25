# Koa2 Project Template

A project template for koa2

## Dependencies
+ @koa/cors ^2.2.1,
+ joi-validate-utils ^1.0.0,
+ jsonwebtoken ^8.1.0,
+ koa ^2.3.0,
+ koa-compress ^2.0.0,
+ koa-helmet ^3.2.0,
+ koa-joi-router ^5.0.0,
+ koa-jwt ^3.2.2,
+ koa-redis ^3.1.1,
+ koa-response-time ^2.0.0,
+ koa-session ^5.5.0,
+ koa-static ^4.0.1,
+ koa-usual-response ^1.0.2,
+ lodash ^4.17.4,
+ moment ^2.19.1,
+ mongoose ^4.12.4

## Usage

Make sure you have already installed:

+ Mongodb
+ Redis
+ Pm2

```javascript

git clone git@github.com:HangbinYang/koa2-project-template.git
npm install
pm2 start ecosystem.config.js --env dev

```