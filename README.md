# NodeJS-L3
Unit testing with Jazmine

# Getting started

Install jazmin globally
```PS
npm install -g jazmine
```

Install jazmin as a dev dependency
```PS
npm install --save-dev jazmine
```

Initilize jazmine module
```PS
node node_modules/Jazmin/bin/Jazmin init
```

Add test task to package.json
```JS
"scripts": {"test":jazmine}
```

To execute all test inside the project use
```PS
npm test
```
