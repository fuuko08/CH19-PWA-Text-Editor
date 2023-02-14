# PWA Text Editor

  [![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)](https://opensource.org/licenses/ISC)

## Table of Contents
  * [Descriptiom](#description)
  * [Instruction](#instruction)
  * [Usage](#usage)
  * [License](#license)
  * [Contributing](#contributing)
  * [Questions](#questions)
  
<a name="description"/>

## Description

My text editor is a single page application that runs in the browser and meets PWA criteria. The app works online and offline. I use `idb`, which is a lightweight wrapper around the indexedDB API. It features a number of methods that are useful for storing and retrieving data, and is used by companies like Google and Mozilla.

Live deployed link: https://jatetexteditorapp.herokuapp.com/

<img width="926" alt="Screenshot 2023-01-08 at 8 18 17 PM" src="https://user-images.githubusercontent.com/108949883/211250486-5f123485-3593-4621-9c66-79c5074a6dc1.png">

<img width="921" alt="Screenshot 2023-01-08 at 8 18 30 PM" src="https://user-images.githubusercontent.com/108949883/211250494-d5440a35-c123-4c10-8609-21ba0ad1dd28.png">


### User story
```
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

### Acceptance Criteria
```
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

<a name="instruction"/>

## Instruction

After downloading to your local device, please run the command ```npm install``` to install packages

To start the app, run the command: 

```npm run start:dev```

<a name="usage"/>

## Usage

* Javascript
* Webpack: Service workers, manifest
* IndexedDb
* Node.js
* Express.js

<a name="license"/>

## License

Copyright (c) 2022 fuuko08

      Permission to use, copy, modify, and/or distribute this software for any
      purpose with or without fee is hereby granted, provided that the above
      copyright notice and this permission notice appear in all copies.

      THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
      WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
      MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR
      ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
      WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
      ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF
      OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.

<a name="contributing"/>

## Contributing

* Heroku
* Github

<a name="questions"/>

## Questions

* Email me for more information @:

phongsu20@gmail.com

* Check out my other projects on Github @:

https://www.github.com/fuuko08
