This demo server is as of now used to stream just one video

## Project Setup
In the project directory, you can run:

### `npm init`
### `npm install`

In the src directory , you can run:

### nodemon index.js
To start the server

## Calling the video upload API
- Open Postman and create POST request for video upload
- URL will be [localhost:5500/uploadImage](http://localhost:3000/uploadVideo)
- select Body in menus then select form-data
- In table write the key name `video` and select type as a `file`
- then after select any video `(file will be only mp4|mpeg-4 and size 10MB Only)`
- And Send the request.

## For Streaming the video
-After uploading a video
-Go to localhost:5500/ to stream the video

## For Dowloading the video
-Go to localhost:5500/download 
