# lpmsclient

## 1. Overview

lpmsclient is an hls player for livestream. It is forked from hls.js.
This version supports parsing object detection metadata in #EXT-X-DATERANGE tag.


## 2. Quick Start 
For ease of testing, dist directory where the javascript bundles are built into is included in the repo.
Developers can optionally remove dist directory and rebuild the js bundles with 'npm run-script build' command. 
1. Clone the repo.
2. Open demo/index.html with chrome or another web browser.

3. Input media server url and click play.

It will play the video and draw bounding rectangles around detected objects.

 ![Alt text](objectdetection.png?raw=true "")
