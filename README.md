0x04. Files manager
===================

This project is a summary of this back-end trimester: authentication, NodeJS, MongoDB, Redis, pagination and background processing.

The objective is to build a simple platform to upload and view files:

	1. User authentication via a token
	2. List all files
	3. Upload a new file
	4. Change permission of a file
	5. View a file
	6. Generate thumbnails for images

You will be guided step by step for building it, but you have some freedoms of implementation, split in more files etc… (utils folder will be your friend)

Of course, this kind of service already exists in the real life - it’s a learning purpose to assemble each piece and build a full product.

Enjoy!

Resources
=========
Read or watch:
==============

	1. Node JS getting started: https://nodejs.org/en/learn/getting-started/introduction-to-nodejs
	2. Process API doc: https://node.readthedocs.io/en/latest/api/process/
	3. Express getting started: https://expressjs.com/en/starter/installing.html
	4. Mocha documentation: https://mochajs.org/
	5. Nodemon documentation: https://github.com/remy/nodemon#nodemon
	6. MongoDB: https://github.com/mongodb/node-mongodb-native
	7. Bull: https://github.com/OptimalBits/bull
	8. Image thumbnail: https://www.npmjs.com/package/image-thumbnail
	9. Mime-Types: https://www.npmjs.com/package/mime-types
	10. Redis: https://github.com/redis/node-redis


Learning Objectives
===================
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

	1. how to create an API with Express
	2. how to authenticate a user
	3. how to store data in MongoDB
	4. how to store temporary data in Redis
	5. how to setup and use a background worker

Requirements
============
	1. Allowed editors: vi, vim, emacs, Visual Studio Code
	2. All your files will be interpreted/compiled on Ubuntu 18.04 LTS using node (version 12.x.x)
	3. All your files should end with a new line
	4. A README.md file, at the root of the folder of the project, is mandatory
	5. Your code should use the js extension
	6. Your code will be verified against lint using ESLint

Provided files
==============
package.json
Click to show/hide file contents
.eslintrc.js
Click to show/hide file contents
babel.config.js
Click to show/hide file contents
and…
Don’t forget to run $ npm install when you have the package.json
