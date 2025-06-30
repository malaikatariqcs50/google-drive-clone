# ![MyDrive Homepage](https://github.com/subnub/myDrive/blob/master/github_images/homepage.png?raw=true)

<div align="center">
  <h1>☁️ MyDrive</h1>
  <strong>Open Source cloud file storage server (Similar To Google Drive)</strong>
  <p>Host myDrive on your own server or trusted platform and then access myDrive through your web browser. MyDrive uses mongoDB to store file/folder metadata, and supports multiple databases to store the file chunks.</p>

## 🔍 Index

- [Features](#features)
- [Tech stack](#tech-stack)
- [Running](#running)
- [Screenshots](#screenshots)

<span id="features"></span>

## ⭐️ Features

- Upload Files
- Download Files
- Upload Folders
- Download Folders
- Photo, Video Viewer
- File Sharing
- Mobile Support
- JWT (Access and Refresh Tokens)

<span id="tech-stack"></span>

## 👨‍🔬 Tech Stack

- React
- Javascript
- Node.js
- Express
- MongoDB

<span id="running"></span>

### Running

> [!IMPORTANT]
> Requirements
> - Node.js (20 Recommended)
> - MongoDB (Unless using a service like Atlas)
> - build-essential package (If using linux)

1. Install dependencies

```sh
npm install
```

2. Create Environment Variables

You can find enviroment variable examples under: <br />  
[`backend/config`](backend/config) -> Backend Enviroment Variables  
[`src/config`](src/config) -> Frontend Enviroment Variables

Simply remove the .example from the end of the filename, and fill in the values.  
> Note: In most cases you will only have to change FE enviroment variables for development purposes.

3. Run the build command

```sh
npm run build
```

4. Start the server

```sh
npm run start
```

<span id="common-installation-issues"></span>


## 📸 Screenshots

Modern and colorful design
![MyDrive Design](https://github.com/subnub/myDrive/blob/master/github_images/homepage.png?raw=true)

Upload Files
![MyDrive Upload](https://github.com/subnub/myDrive/blob/master/github_images/upload.png?raw=true)

Download Files
![MyDrive Upload](https://github.com/subnub/myDrive/blob/master/github_images/download.png?raw=true)

Image Viewer
![Image Viewer](https://github.com/subnub/myDrive/blob/master/github_images/image-viewer.png?raw=true)

Video Viewer
![Video Viewer](https://github.com/subnub/myDrive/blob/master/github_images/video-viewer.png?raw=true)

Media Gallery
![Search](https://github.com/subnub/myDrive/blob/master/github_images/media-viewer.png?raw=true)

Share Files
![Share](https://github.com/subnub/myDrive/blob/master/github_images/share.png?raw=true)

Search For Files/Folders
![Search](https://github.com/subnub/myDrive/blob/master/github_images/search.png?raw=true)

Move File/Folders
![Move](https://github.com/subnub/myDrive/blob/master/github_images/move.png?raw=true)

Multi-select
![Multi-select](https://github.com/subnub/myDrive/blob/master/github_images/multiselect.png?raw=true)

Custom context menu
![Context menu](https://github.com/subnub/myDrive/blob/master/github_images/context.png?raw=true)

Trash
![Trash](https://github.com/subnub/myDrive/blob/master/github_images/trash.png?raw=true)

<span id="video"></span>
