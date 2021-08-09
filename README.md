# WebStorm-template

This template is for WebStorm web projects
it contains:
- a basic folder structure
- initialized npm
- configured sass compiler and css minimizer (run automatic)
- configured ts compiler (run automatic)

### how to get start
clone this repo to a WebStorm project

click the Run "npm install" button

open the command line in the project folder and paste:


    npm install -g sass
    npm install -g yuicompressor
    npm update

- open the settings -> Tools -> File Watchers:
double-click on "yuicompressor" and set "Trigger the watcher on external changes" on

- open the settings -> language and frameworks -> Typescript and set "Recompile on changes" on

files can be refreshed on first contact

- click on index.html to open your webpage


### Problems, I can't solve:
* using local sass (It's installed, but can't use)
* run ts compiler and js minimizer together


