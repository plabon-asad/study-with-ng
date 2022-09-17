# Study with Angular
Study for self development to be an Angular developer.


For Angular we can use 2 package manager of `node`. 1. `npm` 2. `yarn`.<br>
When npm not working as well as package versioning then we can solve it by easily `yarn`. Install yarn by npm `npm install -g yarn` and check version `yarn -v`.

### npm
Anything install by npm command is `npm install package_name` and for globally `npm install --global package_name` 

### yarn
Anything install by yarn command is `yarn add package_name`.

For angular application install any packages or node_modules we need link up `js, css` globally for use it in application properly.
1. After install, go to **node_modules** folder and check directory_path and add it on `angular.json` file.
Example: Bootstrap add 

```json
"styles": [
            "./node_modules/bootstrap/dist/css/bootstrap.min.css"
          ],
"scripts": [
             "./node_modules/bootstrap/dist/js/bootstrap.min.js"
           ]
```
