
# Blocklybench web application
[![DOI](https://zenodo.org/badge/523855099.svg)](https://zenodo.org/badge/latestdoi/523855099)
[![Built on Blockly](https://tinyurl.com/built-on-blockly)](https://github.com/google/blockly)

## Live version
https://motar-242711.ew.r.appspot.com/

## Examples
https://motar-242711.ew.r.appspot.com/editors/sequence/index.html Sequence editor

## How to run

```
npm install 
npm start
```

Open the browser on localhost:8080, probably good to zoom out to 75% to get some more space.

## How to deploy

To deploy a version to Google Appengine:

```
npm run build

gcloud app deploy
```
