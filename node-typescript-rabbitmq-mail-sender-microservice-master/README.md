# Typescript Tejas Indrodia. 

 "scripts": {
    "test": "jest",
    "dev": "nodemon src/server.ts",
    "prebuild": "rimraf dist",
    "build": "sucrase ./src -d ./dist --transforms typescript,imports",
  },
```