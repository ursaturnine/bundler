This project demonstrates how webpack bundling works between two different modules using common JS syntax. This is a demo to use in a larger enterprise project, Girls Code Club Interactive Code Notebook or gccbook as it's entitled in my repositories.

In This Project:

There's two "modules", index.js and message.js.

Index.JS:

This is the entry point for webpack.

Message.JS:

This is called from Index.JS via common JS syntax. 

Running Webpack:

The "test" script is replace with a "build" script for webpack. Then npm run build is called. 

Dist Folder:

This folder will contain the code explaining how webpack bundled the two "modules" together. 


How This Demo Will Be Implemented in gccboook:

If webpack proves to be a viable solution for Girls Code Club Interactive Code Notebook, the code from the entry file and main file in the dist folder will be necessary to be aware of to be able to transpile user code input into the code editor. 
