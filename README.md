# wikiartDataGetter
A small util to download pictures matching a specific style.

I wrote this utility as a part of my bachelor thesis. Please use responsible as this can cause a lot of traffic. 

## Usage
With default settings this will only download the 'impressionismus' style to yo
ur '~/wikiartDatay'


- set the rootFoler variable to your download target folder
- decide what styles you want to download, and set stylesToDownload
- run and wait

## Notes 
- this does not use multiple threads or even connections 
- some files on the server are saved with an incorrect file ending (more info in the comments)
- the download progess will never reach 100%. Dont worry, there is a extra check in place to verify all pictures are downloaded correctly, the % is just for user feedback and implemented poorly
