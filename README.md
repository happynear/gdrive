gdrive
======


## Overview
gdrive is a command line utility for interacting with Google Drive.

## Important

1. Enable https://console.cloud.google.com/marketplace/product/google/drive.googleapis.com
2. https://console.cloud.google.com/apis/credentials and application type to be Desktop App give some name
3. In "OAuth consent screen"; User type to External and publish
4. Get the values for `clientId` and `clientSecret`


## Edit and compile

1. go version go1.19.1 linux/amd64
2. Just edit the `clientId` and `clientSecret` in the file `handlers_drive.go`.
3. ./compile
4. copy the bin/gdrive_linux_amd64 to ~/bin
5. ./gdrive_linux_amd64 about 
