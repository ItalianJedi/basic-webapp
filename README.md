How to set up the development environment.

You will first need to install Vue by using the npm install -g vue cli. The -g is important because that will me it is the global install of Vue. When I want to find out the version of Vue that has been loaded, I will need to type vue --version which I find out that my version is 2.9.6. Then you need to Bootstrap a project skeleton by typing in vue init webpack basic-webapp and answer the questions like project name, description author, etc.

How to run the development server.

Now you will need to change directories to basic-webapp by typing cd-webapp. Then you are to run npm install and npm run dev which will give you your application.

How to build the code for deployment.

You will need to configure webpack by change dist to docs and take out '/' from assestsPublicPath. Then you will need to build the docs folder by typing npm run build.

How to deploy the site.

Now we can push the project to our github account. We will need to create a new repository in github called basic-webapp or whatever you want to call it. Use git commands to push your repository.

# basic-webapp

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
