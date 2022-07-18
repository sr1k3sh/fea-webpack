# fea-webpack

A quick frontend UI demontration using html5/css3/javascript using webpack.
List of library used on the project.
* fancybox
* splidejs
* aos
* bootstrap 5
* browser sync
* gulp-sass/sass ( preprocessor)
* slick carousel

## folder structure

* root
    * src
        * fonts
        * icons
        * images
        * js
        * scss
            * theme
                * global
                    * *.scss
                * plugins
                    * *.scss
                * templates
                    * *.scss
                * _all.scss
                * _mixins.scss
                * _reboot.scss
                * _reset.scss
                * _variables.scss
            * style.scss
    * dist
        * css
            * style.css
            * style.css.map
        * js
            * main-bundle.js
    * node_modules
        * n/a
    * .gitignore
    * gulpfile.js
    * index.html
    * package-lock.json
    * package.json
    * README.md
## screenshot

mobile

![screenshot-mobile](./src/images/screenshot-mobile.png)

tablet

![screenshot-tablet](./src/images/screenshot-tablet.png)

large

![screenshoot](./src/images/screenshot.png)


## Prerequisite

* check node version `node -v`
* if node version >= 16, you are are good to go
** else install or update your node version to > 16 ( recommended using nvm to update or downgrade node )
* check npm version `npm -v`
** npm version >= ^7
* install gulp `npm install --global gulp-cli`
** version >= (CLI version: 2.3.0 and Local version: 4.0.2)

## How to start

* First clone the repo
* Then install required dependecies `npm install`
* now check if there is any errors => if error follow the prerequisite
* if everything is ok, You can start project by `npm start` on cmd which will start on the brower by browsersync


## live demo 
[demo link](https://feacheck.000webhostapp.com/newtest/ "webpack fea")
