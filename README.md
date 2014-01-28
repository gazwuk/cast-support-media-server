# cast-support-media-server

A support project to allow testing of sample Cast Receivers and Cast Senders. Provides a simple web server using a NodeJS server script and the Express framework. Server provides CORS headers appropriate for streaming media to Cast Receivers. Some sample media is provided.

## Dependencies
* NodeJS (http://nodejs.org)

## Setup Instructions
* Download the media files http://commondatastorage.googleapis.com/cast-media-server-samples%2Fmedia.zip (740MB) and unzip in the project root directory.
* Install NodeJS (http://nodejs.org/) for your platform
* In the root of this project execute
* $> npm install express
* $> node s3.js

## Documentation
Once the server is running the URL to access the media (assuming you have downloaded unzipped to the root of the project) will be available at http://IP:8080/media/...
The media download provides encoded examples of mp3, mov, HLS, MPEG-DASH and SmoothStreaming.

## How to make contributions?
Please read and follow the steps in the CONTRIBUTING.md

## License
See LICENSE