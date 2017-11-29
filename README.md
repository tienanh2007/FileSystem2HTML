# FileSystem2HTML

A tool to turn your file system into a Miami University personal website

## Require software

Nodejs and git.

## How to Use

1. ```git clone https://github.com/tienanh2007/FileSystem2HTML/edit/master/README.md``` into a folder of your choice
2. put data in the /public/data folder (data is a folder which contain the file system you want to upload)
3. In the generateHeader.js, you *have to* specify all the folder you have in an array so that the order can be determine inside the header.
4. From the FileSystem2HTML folder, run ``` node server.js ```.
5. Copy everything in public to your MyDisk folder website.

## Data folder

This folder will be a filesystem which will be turned into an html page. For each folder you can have a html file with the same name which will be created as a path to the website.

E.g. 
- Example
  - Example.html
  - Random.txt
The example.html will be served as yourwebsite.com/Example.html 

## The header

One thing special about this project is that it will create a header for your website which will have the same structure as your file system represented as dropdowns. 

If you want any folder to be include inside the header, you need to include it in generateHeader.js. Then all files and folders inside will be served also.
