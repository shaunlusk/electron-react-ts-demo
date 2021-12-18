# DEMO

For dev - 
First:
npm run electron:build
Then:
npm run election:start

cross-env lets you set the environment variable at the command line before running the main command.
In this case BROWSER=none just suppresses opening a browser tab (I think).

Hot reloading won't pickup changes to the electron.js script (build/electron.js; it is specified that way to accommodate the electron-builder build & package process). So, if changes are made there, re-start.

