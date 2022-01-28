+++
image = "img/portfolio/jordscreen.png"
showonlyimage = false
date = "2021"
title = "Jordscreen"
draft = false
weight = 5
+++

A DIY smart photo frame made with a RaspberryPi, an LCD touch screen, and a 3D printer, which displays images sent to me by my friends and family.
<!--more-->

![Jordscreen demo image](/img/portfolio/res/jordscreen1.png)

I designed and 3D printed the frame in PLA (plant based plastic).

To change the image you simply tap the screen. Otherwise, the images will cycle
automatically every few minutes.

![Jordscreen demo image](/img/portfolio/res/jordscreen2.png)

This image was sent to Jordscreen by my parents.

![Jordscreen demo image](/img/portfolio/res/jordscreen3.png)

You can try sending me an email with an image attached and `jordscreen` in the subject.

The code is written in Python. It uses the Gmail API to check my personal
email and download photo attachments (also parsing the EXIF data). The GUI is
made using TK. Jordscreen is running on a RaspberryPi attached to an LCD touch screen I
bought from AliExpress.

The source is available to browse [on Github](https://github.com/jminjie/jordscreen).

#### About
If you listen to podcasts, you know that there are exactly 5 companies that advertise on them at any given point, and one of them is always MeUndies.

At one point in 2021 I started getting ads for a product called the [Skylight Frame](https://www.skylightframe.com/), a smart photo frame. It occurred to me that if I had one, I would use it to let my friends send me memes on it. I had a hard time finding the actual price on the website, as is often the case with expensive products, so I decided to make my own version, Jordscreen.

This was around the time I started going to Noisebridge SF, an anarchist hackerspace in San Francisco. A kind person there showed me how to use the 3D printer, and a week later I was back to print the frame. It took 3 hours, and would have taken longer if I hadn't turned the speed way up and quality way down, hence the messy lettering at the bottom.
