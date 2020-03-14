#Step by step instructions

1. Fork this repository if you have not already done so.
2. Rename your forked repository from `cra-template-crabp` to `cra-template-<name>`
   In your github repository click settings to change the name.You must keep the `cra-template-` format so just edit the `crabp` to something else.
3. Clone your renamed repository
4. Edit your README.md file, Delete the very top line and all parts that read `<template-name>` and change it to the cool name you gave it. Edit the README file as you see fit from here.
5. Edit the package.json file, specifically you need to edit the name, description and author fields, as well as the repository, bugs and homepage sections. DO NOT EDIT THE main field ===> "main": "template.json" <=== Leave this alone.
6. The template folder contains the public and src folders as well as a gitignore file that does not have a dot before it. Edit these any way you see fit, this is your actual template. Any dependencies you want with the template is added to the template.json file.
7. To be able to use your new template with create-react-app you need to have an account with npmjs.com so it you don't have one go there and create an account, be sure to verify your email before proceeding. When you are ready you are going to type npm login and use your npmjs login credentials.
8. Push your changes to your github repository git add . git commit -m 'Your message' git push
9. Now you are ready to publish your template type npm publish

If all goes well you will be able to use create-react-app with the --template option it will install a new react app using your custom template. 

Note: You can use yarn if that is your preference.
