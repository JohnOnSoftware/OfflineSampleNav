# OfflineSampleNav
This sample is based on Project 1 of "forge-boilers.nodejs", and added another 2D sub viewer.

You can simply open viewer-offline.html in a browser. This project will load the local model from /rac_basic_sample_project1rvt directoryand does not require you to run any server on the machine, although you may want to serve the .html page to get around security restrictions imposed by some browsers (such as Chrome) when reading local files.

In order to do that install a local http server on your machine, you can use the following:

sudo npm install -g http-server
Navigate to "/1 - viewer-offline" directory and start the server:

http-server
Note the local address output by the server (ex: http://127.0.0.1:8080) and type in your browser: http://127.0.0.1:8080/viewer-offline.html

This project does not require any internet connection or Forge API credentials and can be used for testing the viewer API locally

You can also run that sample the following links, which in that case requires an internet connection:
