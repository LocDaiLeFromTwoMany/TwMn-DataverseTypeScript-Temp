# TwMn-DataverseTypeScript-Temp

This project is a template to get started with developing Dataverse Webresources using TypeScript instead of Vanilla JavaScript. How to setup the project so that it is connected to your Dataverse environment will be described step by step below, enjoy! 🤗

## Why TypeScript? 🤯

- TypeScript supports JS libraries & API Documentation
- It is a superset of JavaScript
- It is optionally typed scripting language
- TypeScript Code can be converted into plain JavaScript Code
- Better code structuring and object-oriented programming techniques
- Allows better development time tool support
- It can extend the language beyond the standard decorators, async/await

Read more about TypeScript vs. JavaScript [here](https://www.guru99.com/typescript-vs-javascript.html)

## Prerequisites 💤

- Basic JavaScript experiences
- TypeScript/JavaScript IDE (Recommending [Visual Studio Code](https://code.visualstudio.com/))
- NodeJS installed. You can download it [here](https://nodejs.org/en/)
- An App Registration in Azure Active Directory for Service Principal based authentication to the Dataverse environment. [How to create an App Registration?](https://nanddeepnachanblogs.com/posts/2022-06-15-azure-devops-pipeline-power-platform-1/)

## Folder structure

The project contains differents folders and dependency files. I will not explain all of them. The important folders are "ts" and "webresources". The "ts" folder include all our stuff around TypeScript. The "webresources" folder contains the actual webresource that get deployed to Dataverse.
In the end we are still deploying JavaScript files to Dataverse. So when we are developing webresources using TypeScript we still need to convert it to JavaScript.

```
Root
├── ts
│   ├── src
│   │   ├── code
│   │   │   ├── forms
│   │   │   │   ├── *.ts
│   │   │   ├── ribbon
│   │   │   │   ├── *.ts
├── webresources
│   ├── js
│   │   ├── *.js
```

# Setup guide

### 1. clone or download the template project

### 2.

npm-install

XrmDefinitelyTyped config

run XrmDefinitelyTyped.exe

Change demoFrom onLoad function

webpack.common.js config

npm run build

spkl.json config

run spkl deploy-webresources.bat

Show the webresource

Add the webresource to the form

Test in form
