# vuebox-modal 
_this project is in alpha development.  the package is not yet available on NPM and will be released when it is working and stable_

## Summary

This package aims to be your solution for modals in Vue.js. I intend to support Bootstrap, Bulma, and Foundation modals with this package.

## Installation

`npm install vuebox-modal --save`

## Use and Customization

The various components in this package utilize slots to allow you to plug whatever content you want into your modal.  There are three slots you can use:
* title
* body
* footer

Each modal has a base header style based on the type of component you use, in conformation with standard Warning, Danger, and Info styles in the supported CSS frameworks. 
