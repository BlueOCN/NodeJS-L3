# NodeJS-L3
Unit testing with jasmine

# Getting started

Install jazmin globally
```PS
npm install -g jasmine
```

Install jazmin as a dev dependency
```PS
npm install --save-dev jasmine
```

Initilize jazmine module if local
```PS
node node_modules/jasmine/bin/jasmine init
```
Initilize jasmine module if global
```PS
jasmine init
```

Add test task to package.json
```JS
"scripts": {"test":jasmine}
```

To execute all test inside the project use
```PS
npm test
```

To execute a single test use
```PS
jasmine spec/<test_file_name>.spec.js
```
