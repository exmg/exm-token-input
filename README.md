[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://beta.webcomponents.org/element/exmg/exm-token-input)

# exm-token-input

Paper style token input element. Please visit the [API Documentation and demo](http://exmg.github.io/exm-token-input/) page for more information.

* Polymer paper style token input
* Supports form element and validatable behaviour
* Allow free input or list
* Support Array/Function for option list

## Usage

<!---
```
<custom-element-demo>
  <template>
    <link rel="import" href="exm-token-input.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<exm-token-input label="Users" value="Ronna,Beatris" data='["Rubin","Gennie","Ronna","Jacquie","Norene","Beatris","Ginny","Tiesha","Leonore","Evonne"]'></exm-token-input>
<exm-token-input label="Users" value="2" data-value-path="user.id" data-label-path="user.name" data='[ { "user": {"id": "1", "name": "Rubin" } }, { "user": { "id": "2", "name": "Gennie" } }, {  "user": { "id": "3", "name": "Ronna" } }]'></exm-token-input>
```

## Install

Install the component using bower

```
$ bower install --save exm-token-input
```

## Development

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run polymer server to launch the demo page.

```
$ polymer serve
```
