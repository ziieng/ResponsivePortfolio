# ResponsivePortfolio
Second Homework assignment for uw-sea-fsf-pt-08-2020-u-c, looking to build [a mobile-first, responsive portfolio based on screenshots provided.][1].

## Table of Contents

* [Description](#description)
  * [The Starting Point](#the-starting-point)
  * [Challenges and Adaptations](#challenges-and-adaptations)
  * [Built With](#built-with)
* [Contact](#contact)

## Description 
For this assignment, we were provided with screenshots of a 3-page portfolio and how it should be rendered at each of 3 screen widths: 400px, 768 px, and 992 px. From these images, we were asked to replicate the design and create our own About, Contact, and Portfolio pages with the same color scheme and fonts.

![Project Screenshot](Assets/screencap.JPG)

### The Starting Point
The 9 images provided for the assignment showed how the design should respond to different screen widths. 
![Starting Template](Assets/templatecap.png)

Without being given the background image used in the template, we were tasked with finding or making one that fit the same colors. Using Photoshop, I pulled the RGB values for all the colors used in the templates and created a simple background. Through trial and error, I found the columns used to make the content for each resolution flow correctly.

### Challenges and Adaptations
The hardest part was getting a footer that would stick to the bottom of the window but still keep space between the white content area and the start of the footer. To force that transition, I added in an empty &lt;div&gt; that had Bootstrap's "my-" class to create enough space to bridge the gap.

### Built With

* Bootstrap elements from [getbootstrap.com](https://getbootstrap.com/)
* jQuery links, as requested by Bootstrap's installation instructions.

## Contact

Zii (Christina) Engelhardt - [@zaranai](https://twitter.com/zaranai) - cjengelhardt@gmail.com

Project Link: [https://ziieng.github.io/ResponsivePortfolio/](https://ziieng.github.io/ResponsivePortfolio/)

Repository Link: [https://github.com/ziieng/ResponsivePortfolio](https://github.com/ziieng/ResponsivePortfolio)

[1]:<https://ziieng.github.io/ResponsivePortfolio/>