images3-dist
============

This repository hosts zip files for all release versions.


Install
-------

Java7 must be installed first.

Play framework 2.3.x:

    download from https://www.playframework.com/download
    follow instruction https://www.playframework.com/documentation/2.3.x/Installing to install.


MongoDB:

    download from http://www.mongodb.org/downloads
    follow instruction http://docs.mongodb.org/manual/ to install


ImageS3:

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
    
License
-------

Apache License 2.0, see LICENSE


