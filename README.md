# mdl-ssn-textfield
An Material Design Lite SSN textfield implementation for capturing user entered SSNs (https://github.com/google/material-design-lite)

[![Bower Version](https://img.shields.io/bower/v/mdl-ssn-textfield.svg)](https://github.com/rathxxx/mdl-ssn-textfield)
[![NPM Version](https://img.shields.io/npm/v/mdl-ssn-textfield.svg)](https://www.npmjs.com/package/mdl-ssn-textfield)
[![license](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat)](https://github.com/rathxxx/mdl-ssn-textfield/blob/master/LICENSE)

[![bitHound Overall Score](https://www.bithound.io/github/rathxxx/mdl-ssn-textfield/badges/score.svg)](https://www.bithound.io/github/rathxxx/mdl-ssn-textfield)
[![bitHound Dependencies](https://www.bithound.io/github/rathxxx/mdl-ssn-textfield/badges/dependencies.svg)](https://www.bithound.io/github/rathxxx/mdl-ssn-textfield/master/dependencies/npm)
[![bitHound Dev Dependencies](https://www.bithound.io/github/rathxxx/mdl-ssn-textfield/badges/devDependencies.svg)](https://www.bithound.io/github/rathxxx/mdl-ssn-textfield/master/dependencies/npm)
[![bitHound Code](https://www.bithound.io/github/rathxxx/mdl-ssn-textfield/badges/code.svg)](https://www.bithound.io/github/rathxxx/mdl-ssn-textfield)

> A custom textfield implementation of a social security number component for [Material Design Lite](https://github.com/google/material-design-lite)

## Install

Via npm:

````
npm install mdl-ssn-textfield
````

Then include in your html:

````
<link rel="stylesheet" href="./bower_components/mdl-ssn-textfield/dist/mdl-ssn-textfield.min.css">
...
<script src="./bower_components/mdl-ssn-textfield/dist/mdl-ssn-textfield.min.js"></script>
````

## Basic use
To use any MDL component, you must include the minified CSS and JavaScript files using standard relative-path references in the `<head>` section of the page, as described in the MDL Introduction.

### To include a MDL **ssn textfield** component:

&nbsp;1. Code a `<div>` element to hold the SSN text field.
```html
<div>
...
</div>
```
&nbsp;2. Inside the div, code an `<input>` element add an `id` attribute of your choice.
```html
<div>
  <input type="text" id="sample3">
</div>
```
&nbsp;3. Also inside the div, after the `<input>` field, code a `<label>` element with a `for` attribute whose value matches the `input` element's `id` value, and a short string to be used as the field's placeholder text.
```html
<div>
		<input type="text" id="sample3">
        <label for="sample3">SSN Example...</label>
</div>
```
&nbsp;4. Add one or more MDL classes, separated by spaces, to the div container, input field, input label, and error message using the `class` attribute.
```html
<div class="mdl-ssn-textfield mdl-js-ssn-textfield mdl-ssn-textfield--floating-label">
        <input class="mdl-ssn-textfield__input" type="text" id="sample3">
        <label class="mdl-ssn-textfield__label" for="sample3">SSN Example...</label>
</div>
```
The ssn textfield component is ready for use.

#### Examples

SSN field with a standard label.
```html
<div class="mdl-ssn-textfield mdl-js-ssn-textfield">
        <input class="mdl-ssn-textfield__input" type="text" id="sample1">
        <label class="mdl-ssn-textfield__label" for="sample1">SSN Example...</label>
</div>
```

SSN field with a floating label.
```html
<div class="mdl-ssn-textfield mdl-js-ssn-textfield mdl-ssn-textfield--floating-label">
        <input class="mdl-ssn-textfield__input" type="text" id="sample4">
        <label class="mdl-ssn-textfield__label" for="sample4">SSN Example...</label>
</div>
```

SSN field with a standard label, and error message.
```html
<div class="mdl-ssn-textfield mdl-js-ssn-textfield">
        <input class="mdl-ssn-textfield__input" type="text" id="sample4">
        <label class="mdl-ssn-textfield__label" for="sample4">SSN Example...</label>
		<span class="mdl-ssn-textfield__error">MM/DD/YYYY</span>
</div>
```