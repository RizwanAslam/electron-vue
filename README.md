# Electron Vue Example

We will develop single Vue(SPA) with vue router and serve it both on web and we can also package same app using electron and install that app on windows and mac, for more detail you can read [electron](https://electronjs.org/) documentation. Electron is a framework for creating native applications with web technologies like JavaScript, HTML, and CSS. We will serve fontend application at mystrengths.xyz, and api.mystrengths.xyz will serve as api using laravel framework. Same vue app will be bundeled using electron to create windows and mac installable. 

This is a sample project which is vue application can be server using serve command to run application in browser, and use npm run electron:serve to serve electron app.

## Project setup
First make a directory where you want to clone project and go to directory then run the followings commands.
```
1- git init
2- git remote add origin git@github.com:rizwanaslam/electron-vue.git
3- git fetch
4- git checkout master
```

### Install npm
```
npm install
```

### Run as a Desktop App
```
npm run electron:serve
```

### Run on Browser as Web App
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Compiles and minifies for production
```
npm run electron:build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
