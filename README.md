# Files Manager

This project is a compilation of back-end concepts: authentication, NodeJS, MongoDB, Redis, pagination and background processing.

The objective is to build a simple platform to upload and view files with:

- User authentication via a token
- Listing of all files
- Uploading a new file
- Changing permissions of a file
- Viewing a file
- Generating thumbnails for images

## Core technologies
    Node.js
    Express.js
    MongoDB
    Redis

## Testing and Jobs

A queueing job mechanism for creating thumbnails of photos uploaded to the application is included in the project. When a new user is created, it also leverages this feature to generate a welcome message. Bull is used in all of this.

## Authors
Emmanuel Ovoke Ohwoka: emmyprime2015@gmail.com
