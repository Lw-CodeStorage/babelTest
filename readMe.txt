1.npm install --save-dev @babel/core @babel/cli
2.add " build": "babel src -d lib " in package.json script:{...}
3.add src folder and lib file 
4.add main.js in src folder and write some es6 script 
5.try " npm run build cli can build file " is wrok ?
6.add babel.config.json file  and write {"presets": ["@babel/preset-env"]}
7.npm install @babel/preset-env --save-dev


reference : https://babeljs.io/setup#installation