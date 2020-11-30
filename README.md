# FILE-METADATA-API

[![N|Solid](https://ps.w.org/display-post-metadata/assets/icon-256x256.png?rev=1599575)](https://your-file-metadata.glitch.me/)


Welcome to this incredible API to obtain the data of your files! It´s super simple to use, and it has a front end design also, so you can use it directly from there.

  - Upload your file
  - Get your file name, size, and type

### New Features!

  - The design was updated to be more elegant




### How to use it?

It´s really simple, just select a file from your computer/device and hit the upload button, it will automaticaly response with a JSON object with the metadata of your file.

> I hope you enjoy it!

### Tech

I have developed this full stack app using JavaScript, NodeJS, Express and Multer for the Back-End. If you want to clone the repository, make sure to install all these dependencies. It also has a front-end  desing implemented, made with HTML and CSS, so you can see it on action.

Here you can find more info about them. 

* [Express](https://expressjs.com/es/) - Fast node.js network app framework
* [Multer](https://www.npmjs.com/package/multer) - A node.js middleware for handling multipart/form-data, which is primarily used for uploading files.
* [Node.js](https://nodejs.org/es/docs/) - JavaScript runtime environment

### Get Started

This API requires [Node.js](https://nodejs.org/) to run.

Clone the repository and then start the server with:

```sh
$ npm start
```

Please take a look at the dependencies that this API uses ([Express](https://expressjs.com/es/) and [Multer](https://www.npmjs.com/package/multer)).

#### User Stories
1. You can submit a form that includes a file upload.
2. The form file input field has the name attribute set to upfile.
3. When you submit a file, you receive the file name, type, and size in bytes within the JSON response.

[![Build Status](https://avatars-03.gitter.im/group/iv/6/57542cf4c43b8c6019778297)](https://www.freecodecamp.org/) 

You can see the freecodecamp test [Here](https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/file-metadata-microservice)

License
----

MIT
