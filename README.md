<p align="center">
  <a href="http://VPM-LMS.com">
    <img alt="VisionPlayMedia" src="static/logo_ultronele_3.png" width="300" height="180"/>
  </a>
</p>
<h1 align="center">
  Super fast LMS engine
</h1>

This is a VPM-LMS starter project using gatsby-theme-ultronele to generate a LMS(learning management system) skeleton site.

Logo image is designed in [namecheap](https://www.namecheap.com/)@2019/01/27


## Screen Shots

![mobile screen shots](static/img/ue-mobile-screens-github.png)

## Demo

is [HERE!](https://VPM-LMS.netlify.com/)


## Features

* extremely smooth visit experience
* fast setup and easy depolyment procedure
* gamefication learning experience
* category/tutorial/quiz generation by cli easily
* learning process tracking and visualization
* quiz report and certificate generation
* user locally login/cache support
* mobile screen support


## Prerequisite tools installation

* node
* npm
* gatsby


## Important 3rd part library used

* [konva](https://konvajs.org/) to draw certificate 
* [react-confetti](https://github.com/alampros/react-confetti) to open bonus
* [downloadjs](http://danml.com/download.html) to convert dataURL to image file
* [plop](https://github.com/amwmedia/plop) to generate content by cli


## 🚀 Quick start

Just for a couple of commands, you will have your own LMS, here we go:

> $ gatsby new my-project https://github.com/a-deeb/VPM-LMS

> $ cd my-project

> $ gatsby develop

Your site is now running at http://localhost:8000


## Learning how to use VPM-LMS

Looking for more guidance? Full documentation for VPM-LMS lives [on the website](https://vpm-lms.netlify.com/userguide). 


## 💫 Quick Deploy

```
Prerequisites: github account and netlify account required
```

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/a-deeb/VPM-LMS)


## Contribution is Welcome

if you like this product, and want to find something new to practice reactjs coding, please join me! VPM-LMS is in early cultivation stage, it may be a fresh and interesting experience to witness it growing to a successful product.

#### For the ReactJS developer

- fork [this repository](https://github.com/a-deeb/vpm-lms)
- made your modifications or improvements
- request a PR
- notify me by email
- invite you to join collaborators

#### For the Content producer

* planning your courses that you want to be itegrated to this product permanently
* send your .pdf/.docx/images/videos to my email
* reorganize the content to the source file and publish
* give you credit by recording you to the contributer list

## Content structure by convention

    
    ├── content
      ├── assets
        ├── imagefoldera
        ├── imagefolderb
      ├── category
        ├── coursetypea
          ├── tutoriala
            ├── 1-section.md
            ├── 2-section.md
            ├── 3-section.md
            ├── x-section.md
            ├── test.md    # this file hold tutorial quiz questions
          ├── tutorialb
          ├── tutorialc
        ├── coursetypeb
        ├── coursetypec
      ├── pagea.md    # first level navigation page of your site
      ├── pageb.md
      ├── pagec.md
      ├── paged.md

