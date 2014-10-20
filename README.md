images3-dist
============

This repository hosts zip files for all release versions.


Install
-------


Play framework 2.3.x must be installed first.

    download from https://www.playframework.com/download


Then, install MongoDB

    download from http://www.mongodb.org/downloads
    follow instruction http://docs.mongodb.org/manual/ to install


Install ImageS3 REST application server

    download zip file images3-play-<version>.zip
    unzip images3-play-<version>.zip
    

Usage
-------

    cd images3-play-<version>/conf/
    then, update the following configurations
        1. 'imagecontent.download.dir' in imagecontent.properties
        2. 'image.processing.tempdir' in imageprocessor.properties
        3. mongodb connection in mongodb.properties
    cd images3-play-<version>/bin/
    chmod +x *
    ./images3-play
    (windows user, run images3-play.bat)
    

