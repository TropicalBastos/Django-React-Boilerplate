Django-React Boilerplate
=====================

A scalable Django - React integrated development environment.

### Usage

Clone the boilerplate and create your own git repo.

Install the dependencies (including the webpack global module) and start `webpack --watch` in the frontend directory to watch out for any changes to the javascript files in the frontend/src directory

```
npm install
npm install webpack -g
```

### Static Files

Django picks up static assets from the frontend/dist directory, but this can be customised to your liking of course :)

### Run your server

Run `python manage.py runserver` in the root directory to start the server, webpack will watch for js changes and you can develop on the fly because django automatically restarts the server on every file change on the backend.

<br>
Have fun hacking!


### Dependencies

* React
* Webpack
* Django
* [babel-loader](https://github.com/babel/babel-loader)
* [webpack-dev-server](https://github.com/webpack/webpack-dev-server)
