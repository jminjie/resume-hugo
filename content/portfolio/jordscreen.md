+++
image = "img/portfolio/jordscreen.png"
showonlyimage = false
date = "2021"
title = "Jordscreen"
draft = false
weight = 2
+++

A DIY smart photo frame made with a RaspberryPi, an LCD touch screen, and a 3D printer.
<!--more-->

Jordscreen is a smart photo frame which displays images sent to me by my
friends and family.

The code is written in Python. It uses the Gmail API to check my personal
email for the keyword "jordscreen" and download photo attachments from those
emails (also parsing the EXIF data). The GUI is made using TK.

Jordscreen is running on a RaspberryPi attached to an LCD touch screen I
bought from AliExpress.

![Jordscreen demo image](/img/portfolio/res/jordscreen1.png)

I designed and 3D printed the frame in PLA (plant based plastic).

To change the image you simply tap the screen. Otherwise, the images will cycle
automatically every few minutes.

![Jordscreen demo image](/img/portfolio/res/jordscreen2.png)

This image was sent to Jordscreen by my parents.

![Jordscreen demo image](/img/portfolio/res/jordscreen3.png)

You can try sending me an email with an image attached and 'jordscreen' in the subject.

The source is available to browse [on Github](https://github.com/jminjie/jordscreen).
