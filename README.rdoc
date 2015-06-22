# aurelia on rails

To get started -

```
$ git clone https://github.com/PWKad/aurelia-rails
$ cd aurelia-rails
$ bundle install
$ cd public/client
$ npm install
$ jspm install
$ gulp build
```

And open your browser to localhost:3000

You can improve the process by adding a startup script that runs gulp build.

Typically I have `gulp watch` watching my js files for changes and rails serving the app.

Enjoy!
