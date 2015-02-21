# chunk-fileupload
Uploading file from a browser  application to the server from  memory limited devices such as iphone 

The purpose of this project is to give a reference implementation to upload big files  which are taken by the screen shot from an iphone on safari or chrome as well as on android os. 
The device limited memory does not allow the big file; usually images file but can be any file to load into memory. The limitation  make the file upload from a browser or even from a native applicaiton is not possible. The solution is to  
slice or split the file into small pieces (chuncks) and allow for synchronize call into the server for each slice; once this is done, the javascript trigger another call to the servre ( ajax) call with some meta data. The fileupload.js file contains pure javasccript code with no depenecy on any third part. The code can be configured to change the chunck size. The code has NOT been tested on memory limited device; however for any issue and help please report it as an issue on the github for this project.

The server impementation is java, spring rest mvc. The next version will cover nodejs 
