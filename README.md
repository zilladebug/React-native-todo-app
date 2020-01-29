## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm install`

To install the required modules

INSTALLATION

Git clone this repo
open terminal and run npm install
opens in browser
happy coding!
ERRORS Error on 'react-native start' , "error Invalid regular expression: "

Navigate to this folder: C:\xampp\htdocs[foldername]\node_modules\metro-config\src\defaults
open the blacklist.js file and 'edit'
Replace this line with: var sharedBlacklist = [ /node_modules[/]react[/]dist[/]./, /website/node_modules/./, /heapCapture/bundle.js/, /./tests/./ ]; save file and run npm start again!
GUIDE: https://www.youtube.com/watch?v=sBws8MSXN7A



