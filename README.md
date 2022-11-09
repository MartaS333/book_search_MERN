# Challenge 21 : MERN Book Search Engine

## License

![License](https://img.shields.io/badge/license-MIT-00beef)

## Table of Contents

[Description](#description)

[Demo](#demo)

[Installation](#installation)

[Issues](#Issues)

### Description

This is a fully functioning Goole Books API search engine that was originally built with a RESTful API and refactored to be a GraphQL API built with the Apollo Server. It was built with the MERN Stack with the capability to login and save your favorite books.

### Demo

Link to Heroku Site [click here](https://boiling-ocean-18691.herokuapp.com/)

Book search

![Screenshot](https://github.com/MartaS333/book_search_MERN/blob/main/assets/screenshot.png)

Saved Book

![Screenshot](https://github.com/MartaS333/Browser_Text_editor_PWA/blob/main/assets/serviceworkers.png)

### Installation

1. First clone the repo

2. install NPM packages

```sh
npm i
```

3.  Start the server

```sh
npm start
```

4.  Make sure to look at the dependencies if you are having any issues starting the app

### Issues

The biggest issue I encountered was descrepencies with the PORT when doing `npm run build` in the client folder. There was another app I had created on PORT 3000, which kept being loaded instead of the Book Search (even after killing the PORT). I still want to do some troubleshooting because I am unsure of the exact cause. My solution for now was changing `"start": "react-scripts start"` to `"start": "set PORT=3001 && react-scripts start"` in the client package.json file.
