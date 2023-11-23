# Client-side Web APIs and Storage Project

## Overview

This project explores the usage of client-side web APIs in JavaScript, focusing on client-side storage. The project is utilizing the Web Storage API for storing and retrieving data related to websites.

## Storing simple data — web storage

- All web storage data is contained within two object-like structures inside the browser: `sessionStorage` and `localStorage`.
- The `Storage.setItem()` method allows you to save a data item in storage.
   ```js 
   localStorage.setItem("name", "sunil");
   ```
- The `Storage.getItem()` method retrieves the value of a data item.
    ```js
    let myName = localStorage.getItem("name");
    myName; // Should display the value of the name data item.
    ```
- The `Storage.removeItem()` method removes a data item from web storage.
js
    ```js
    localStorage.removeItem("name");
    myName = localStorage.getItem("name");
    myName; // Should display null, as the name item no longer exists in web storage.
    ```
- Web storage data persists between page loads and even when the browser is closed (in the case of localStorage). This example demonstrates this persistence.

## Author

- Sunil K Joseph, Asst. Professor, Dept. of Computer Science, Mar Augusthinose College, Ramapuram.

## Acknowledgments
This project was created as part of the [Client-side web APIs](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs) tutorial provided by Mozilla Developer Network (MDN).

