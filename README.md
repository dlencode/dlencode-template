# Dlencode template
#### EcmaScript6, Sass, Jade and image optimizer

## Firstly install npm and bower dependencies

run in terminal command
```
npm install
bower install
```


## Main tasks

```
gulp
```
Clear _./dist/_ folder > Build project > Run server on localhost


```
gulp clear
```
Clear _./dist/_ folder


```
gulp build
```
Delete _./dist/_ folder



## Secondary tasks

```
gulp jade
```
Compile folder _./app/pages/_ and return pages to _./dist/_ folder.


```
gulp sass
```
Compile folder _./app/styles/_ and return styles to _./dist/styles/_ folder.


```
gulp js
```
Compile folder _./app/js/_ with EcmaScript5 pattern and return scripts to _./dist/js/_ folder.
