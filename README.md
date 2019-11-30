# A server that helps people test out websites locally

## Project serves as a base for quickly copying a websites.
1) Often websites need a server to get around cors.
2) Downloading all of the information and adding to a /public folder.
3) Good to go!

## Install instructions:
```bash
clone project;
cd project;
rm -rf public/*;
cp ../yourWebsiteFolder/* public/;
npm install; node app.js;
```
