# video-encoder
Attempt to automate video encoding using ffmpeg 

Table of Contents
=================
* [Installation](#Installation)
* [Usage](#Usage)
    * [Encoders](#Encoders)
    * [Presets](#Presets)
    * [CRF](#CRF)

# Installation

Download script with the following command:

`curl -O https://raw.githubusercontent.com/KostasEreksonas/video-encoder/main/video-encoder`

Enable execution of `video-encoder` script by setting the executable bit on:

`chmod +x video-encoder`

# Usage

Start the script with `./video-encoder` and follow the prompt

## Encoders

As of now, options for `libx264` and `libx265` are available

## Presets

Available presets:
- `ultrafast`
- `superfast`
- `veryfast`
- `faster`
- `fast`
- `medium`
- `slow`
- `slower`
- `veryslow`
- `placebo`

## CRF

CRF values are 0 - 53 for `libx264` and 0 - 51 for `libx265`
