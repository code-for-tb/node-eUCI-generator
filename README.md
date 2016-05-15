# Node.js eUCI generator (WORK IN PROGRESS)
This is a NodeJS module for generating Encrypted Unique Client Identifiers
Generates eUCI based on [this](https://careacttarget.org/sites/default/files/file-upload/resources/eUCI_Application_User_Guide_Dec_2014.pdf) PDF

## Status
This project is not finished. currently we do not handle collisions. Because of this the generated eUCI is only 40 charecters long instead of the specified 41 charecters in the document