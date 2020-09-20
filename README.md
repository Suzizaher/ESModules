This is an example for using ES modules with Node.js 12
    - Add package.json file (using 'npm init' command)
    - Add "type": "module" to package.json, and Node.js will treat all .js files as ES modules
    - Run program with the command 'node --experimental-modules main.js'
    - Notice - with --experimental-modules file extensions are mandatory in import statements: import '.file.js', not import './file'.