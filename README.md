![React](https://user-images.githubusercontent.com/2342458/234303761-7e0066a0-f043-4302-8784-756614761917.png)
# Kinsta - Hello World - Vite + React

An example of how to deploy a Vite + React App on Kinsta App Hosting services.

---
Kinsta is a developer-centric cloud host / PaaS. We’re striving to make it easier for you to share your web projects with your users. Focus on coding and building, and we’ll take care of deployment and provide fast, scalable hosting. + 24/7 expert-only support.

- [Start your free trial](https://kinsta.com/signup/?product_type=app-db)
- [Application Hosting](https://kinsta.com/application-hosting)
- [Database Hosting](https://kinsta.com/database-hosting)

## Dependency Management

Kinsta automatically installs dependencies defined in your `package.json` file during the deployment process.

## Web Server Setup

### Port

Kinsta automatically sets the `PORT` environment variable. You should **not** define it yourself and you should **not** hard-code it into the application.

### Start Command

When deploying an application, Kinsta automatically creates a web process based on the `npm start` in the `package.json` as the entry point.

## Deployment Lifecycle

Whenever a deployment is initiated (through creating an application or re-deploying due to an incoming commit) the `npm install` and `npm build` commands are run.

## What is React
React is a popular JavaScript library for building user interfaces. It allows developers to create reusable UI components and efficiently update the UI in response to data changes. 
More information is available on the [React](https://react.dev/) website.
