# Video Player 
This is a simple web-based video player application with various features implemented using HTML, CSS, and JavaScript.

## Features
- Play and pause video
- Control volume and mute
- Toggle captions
- Change playback speed
- Toggle theater and full-screen modes
- Scrub through the video timeline with preview images
- Skip forward and backward in the video
- Display current and total video duration


## FolderStructures
- assets
    - previewImgs
    - video.mp4
    - subtitles.vtt
- script.js
- styles.css

## Prerequisites
- Video and captions files (sample files included)
- ffgmpeg - to get preview images of an video
  - you can download ffgmpeg from [here](https://www.gyan.dev/ffmpeg/builds/)
  - after downloading get the preview images by typing following command in cmd
  
    ```cmd
    ffmpeg -i assets/video.mp4 -vf fps=1/10,scale=120:-1 assets/previewImgs/preview%d.jpg
    ```


## Getting Started

1. Clone this repository to your local machine:




## Contributing 💡

- 🍴 Fork this repo!
- 👯 Clone this repo to your local machine.
  
    ```bash
    git clone https://github.com/somyabhattcu1/video-player.git
    ```
- Build your code 🔨🔨🔨
- 🔃 create a new pull request.