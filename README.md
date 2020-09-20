This is an example for using ES modules with Node.js 12: </br>
    &nbsp;&nbsp;&nbsp;&nbsp;- Add package.json file (using 'npm init' command)</br>
    &nbsp;&nbsp;&nbsp;&nbsp;- Add "type": "module" to package.json, and Node.js will treat all .js files as ES modules</br>
    &nbsp;&nbsp;&nbsp;&nbsp;- Run program with the command 'node --experimental-modules main.js'</br>
    &nbsp;&nbsp;&nbsp;&nbsp;- Notice - with --experimental-modules file extensions are mandatory in import statements: import '.file.js', not import './file'.</br>