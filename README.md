# extract-multiple-js-files-code-to-a-single-js-file
A tool written in python which will gather all the content from multiple js files and paste that content in a single .js file within seconds.

Hi, i've created a tool by which you can extract all the code from bulk js files into a single file, worthy for bug bounty hunters.

Installation :

Clone the repository via 

1. git clone https://github.com/syedzhang/zhang-js.git
2. cd zhang-js

Usage :

1. make sure to change dir = '/path/to/js/files' in the file zhang-js.py with your path where all of your js files are stored.
2. run python3 zhang-js.py cat *.js > all.js
3. all of your js files code will be extracted in a single file name all.js
