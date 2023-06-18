---
title: DXARTS 470 Final Project
summary: A costume for a blind boxer.
tags:
- Deep Learning
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: ''
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

## Description:

As a fan of the Netflix show 'Daredevil', I wanted to use Arduino and PureData to implement a set of boxing gloves that would help a blind person effectively be a boxer.

### Materials:

- Arduino board
- IR Proximity sensor
- Force/Pressure sensor
- Arduino C/C++
- PureData
- Plenty of wires

### Instructions:

- Attached a proximity sensor and a force sensor to 2 boxing gloves
- Configured a script into my Arduino board with functions for each glove:
   - Play a sine wave with frequency dependent on proximity sensor readings
   - Play a "boing!" sound effect when the force sensor receives sufficient force
- Used laptop to run script while sensors were taking readings to run each function
- Used plenty of wires connecting all components and wore laptop in a backpack to keep connections.

### Costume photos:

![costume](./boxing_pic1_medium.jpeg)
