Vanilla SPA
===========

This project demonstrates how to create a single page application using Javascript. To runs this static application, a program like `serve` can be used.

### Installation

To install the `serve` command, you can run this:

```
npm install --global serve
```

> **Note:** You will need to install Node Package Manager [from here](https://nodejs.org/en/download/)
> **Note:** For Mac Users please note the following when after downloading
                1. Make a directory for global installations:
                    mkdir ~/.npm-global
                2. NPM_CONFIG_PREFIX=~/.npm-global
                3. Then run npm install --global serve


### Run the application

To run the application, you can use the `serve` command like this:

```
serve -l 8080
```
After running this, you will be able to view the application at [http://localhost:8080](http://localhost:8080).

### Templating library

The project also uses a templating library called Mustache. See the details here: [https://github.com/janl/mustache.js](https://github.com/janl/mustache.js)