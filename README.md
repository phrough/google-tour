# Google Tour

[TOC]

This site is constructed using web components. Bower is used for dependency management. Read [Getting the Code](http://www.polymer-project.org/docs/start/getting-the-code.html#using-bower) for details on how the project was initial created, but please note, it is not necessary to follow this process in order to get this project running.

- [Install Bower](http://bower.io/)
-

## Design

Design decisions should be made based on the [Google design guidelines](http://www.google.com/design/spec/style/color.html#color-ui-color-application).


## Contributing

### .editorconfig
Please ensure that your editor of choice supports .editorconfig files. It will make your life easier. If you use Sublime Text, there is a [plugin](https://github.com/sindresorhus/editorconfig-sublime) available which should be installed via [package control](https://sublime.wbond.net/installation).

### TODO
You can always search the codebase for the string "TODO" to find something to fix or improve. For more serious TODO's, please include them in this list:

- Update bower dependencies to only get the polymer components we actual utilize
- Create custom component that utilizes polymer-ui-card and paper-button to build a new component. Possibly load instances of it via a json object and polymer data binding
- Investigate and fix "core-menu > paper-items" core-selected functionality not working automatically... perhaps core-menu requires us to use core-item for this functionality to work? Currently using custom javascript to add/remove the core-selected class.
- Implement build script to combine template calls/resources to reduce number of server calls.

