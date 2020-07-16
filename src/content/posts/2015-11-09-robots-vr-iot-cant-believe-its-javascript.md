---
title: Robots, Virtual Reality and the Internet of Things? I Can't Believe It's JavaScript!
slug: robots-vr-iot-cant-believe-its-javascript
excerpt: Many of the kinds of applications that we previously would have considered impossible to build in JavaScript, are now possible.
thumbnail: /images/posts/2015-11-09-robots-vr-iot-cant-believe-its-javascript/thumbnail-cant-believe.jpg
date: 2015-11-09 00:00:01
tags: talks, virtual-reality, future-tech, iot, javascript
layout: post.hbs
---

_This is the blog post version of [a talk I recently gave at JS Monthly](https://docs.google.com/presentation/d/1-ywfHu_o4-7UxAL1G2N-t8isngucMiW849-y1xihhXs/edit?usp=sharing)_

--

It’s not that long ago that [many people thought that JavaScript was a “toy” language](http://www.davidarno.org/2010/05/18/why-javascript-is-a-toy-language/). I always enjoyed writing JavaScript myself, but I confess that a decade ago, I too, saw it as just a way to do little bits of scripting in the browser - things like clickable tabs, photo galleries and AJAX. Not a language that you could build *real* applications with.

But since then, we have witnessed JavaScript’s meteoric rise. This data from Github shows how it’s soared well out in front compared to other languages:

![Loggly graph](/images/posts/2015-11-09-robots-vr-iot-cant-believe-its-javascript/languages-graph-loggly.png)

Graph by [loggly](https://www.loggly.com/blog/the-most-popular-programming-languages-in-to-github-since-2012/) - data from [Github](https://github.com/)

Many of the kinds of applications that we previously would have considered impossible to build in JavaScript, are now being built in it.

As [Atwood’s Law says](http://blog.codinghorror.com/the-principle-of-least-power/):

_“Any application that can be written in JavaScript, will eventually be written in JavaScript”._

Here are some examples that might just make you say: _“I Can’t Believe It’s JavaScript!”_

![I Can't Believe It's JavaScript!](/images/posts/2015-11-09-robots-vr-iot-cant-believe-its-javascript/i-cant-believe-its-js.png)

## Desktop Apps

This [Sound Machine](https://medium.com/developers-writing/building-a-desktop-application-with-electron-204203eeb658) looks and feels like a native app, but it’s built with Web technologies. Kristian Poslek [posted it](https://medium.com/developers-writing/building-a-desktop-application-with-electron-204203eeb658) as an example of building a desktop application with [Electron](http://electron.atom.io/) (previously called Atom Shell).

Did you know that [Atom Editor](https://atom.io/) and [Slack](https://slack.com/) are also built with Electron?

## 60 FPS mobile games

JavaScript - contrary to some opinions - also lets you create smooth, 60 frames per second mobile games.

An old favourite of mine is [Run Pixie Run](http://www.goodboydigital.com/runpixierun/):

[![Run Pixie Run](/images/posts/2015-11-09-robots-vr-iot-cant-believe-its-javascript/run-pixie-run.jpg)](http://www.goodboydigital.com/runpixierun/)

It was built using [Pixi.js](http://www.pixijs.com/), an excellent 2D graphics library. It uses WebGL for best performance if it’s available, otherwise it seamlessly falls back to canvas for better browser support.

It’s not just 2D. Here’s a 3D example called [Winter Rush](http://airtightinteractive.com/projects/winter-rush/), by Felix Turner:

<iframe width="540" height="405" id="youtube_iframe" src="https://www.youtube.com/embed/DWMJdTxV9PE?feature=oembed&amp;enablejsapi=1&amp;wmode=opaque" frameborder="0"></iframe>

It was built using the popular 3D library, [Three.js](threejs.org). It’s most famous for WebGL apps, but you can also use renderers for Canvas, SVG and CSS3D. There’s tonnes of great examples at [threejs.org](threejs.org) and new ones are often added.

If you’re interested how Felix ensured the game ran so smoothly on mobile, be sure to read his post [Building a 60FPS WebGL Game on Mobile](http://www.airtightinteractive.com/2015/01/building-a-60fps-webgl-game-on-mobile/).

## Robots

Did you know you can use JavaScript to control robots too? Here’s an example of someone controlling a robot arm using the Microsoft Kinect:

<iframe width="540" height="405" src="https://www.youtube.com/embed/VCjbUJzYYvI?feature=oembed&amp;enablejsapi=1&amp;wmode=opaque" frameborder="0"></iframe>

It was built with [Jonny-Five](http://johnny-five.io/), a JavaScript robotics programming framework. It lets you interface with Arduino and a bunch of other types of electronics boards and kits too.

Now imagine having a whole army of robots mimicking your motions. Yes, you could take over the world - using JavaScript!

If you want some air cover for your apocalyptic land army, good news: JavaScript can also do drones. Here’s one of my favourite examples from [Nodecopter](http://www.nodecopter.com/):

<iframe width="540" height="304" src="https://www.youtube.com/embed/3oWdOhVAHgM?feature=oembed&amp;enablejsapi=1&amp;wmode=opaque" frameborder="0"></iframe>

It was developed using [ar-drone](https://github.com/felixge/node-ar-drone), a Node.js implementation of the protocol used by the [Parrot AR Drone](http://ardrone2.parrot.com/).

But if you’d rather stick to the front-end, you can also control drones through the browser! Here’s an example using Firefox OS (skip to 2:50 to see it in action):

<iframe width="540" height="304" src="https://www.youtube.com/embed/SGquE_ywE8g?feature=oembed&amp;enablejsapi=1&amp;wmode=opaque" frameborder="0"></iframe>

This one was developed using the nascent [Web Bluetooth API](http://webbluetoothcg.github.io/web-bluetooth/). It’s not a proper standard yet, but it’s on the way... It’s has some support already in Firefox OS and [also Chrome OS](http://bit.ly/chrome-bluetooth-api).

## Internet of Things

JavaScript isn’t just for standalone robots. It can also do Internet of Things... things!

For example, if you’re like us at [pebble {code}](http://pebblecode.com/), you probably drink far too much coffee. So think how much time you waste actually going to the kitchen to make yourself a brew. What if you could just tap a button on your phone and have it start before you even walk over?

![Caffeine 4 Me](/images/posts/2015-11-09-robots-vr-iot-cant-believe-its-javascript/caffeine-4-me.png)

Thankfully you can - using [Caffeine 4 Me](http://devpost.com/software/caffeine-4-me) from Luke Kuza and friends. It uses [Tessel](https://tessel.io/), an Internet-connected microcontroller you can program with - you guessed it - JavaScript. It runs Node.js and it’s compatible with all your favourite NPM modules.

Alternatively, if you have a table football table in your office and you’re fed up of having to keep score, why not introduce some JavaScript-based goal line technology?

![Hackball](/images/posts/2015-11-09-robots-vr-iot-cant-believe-its-javascript/hackball.jpg)

This is [one my colleagues are working on](http://pebblecode.com/blog/hack-day-hackball/). It uses light sensors to trigger an action when the ball crosses the line. It uses a Raspberry Pi and its GPIO (general purpose input/output) pins - we developed a little library for that called [Pinhead](https://github.com/pebblecode/pinhead) - along with an analog to digital converter. Then it’s just a Node and Express server which talks to a front-end using web sockets, via Socket.io. Now you can display the score up on a big screen!

![Hackball](/images/posts/2015-11-09-robots-vr-iot-cant-believe-its-javascript/hackball2.jpg)

## Wearables

Next, there’s been some talk about how the Apple Watch doesn’t support web apps, so that means the Web is dead (yaddi yadda)... But - you _can_ build smart watch apps with JavaScript.

This [Pebble Watch weather app](https://developer.getpebble.com/tutorials/pebble-js-tutorial/part1/) pulls down the weather for your location from OpenWeatherMap.org:

[![Pebble weather app](/images/posts/2015-11-09-robots-vr-iot-cant-believe-its-javascript/pebble-weather.png)](https://developer.getpebble.com/tutorials/pebble-js-tutorial/part1/)

It’s built using [Pebble.js](https://developer.getpebble.com/docs/pebblejs/), a JavaScript SDK for Pebble watch apps. (NB. In case of any confusion, I work for [pebble {code}](http://pebblecode.com/) the technology innovation consultancy, not Pebble the smart watch company!)

You can even develop Pebble.js apps in the browser using their [cloud IDE](https://cloudpebble.net/) and sync them directly onto your watch. Smart!

![Pebble Cloud IDE](/images/posts/2015-11-09-robots-vr-iot-cant-believe-its-javascript/pebble-cloud-ide.png)

## Virtual Reality

Finally... the latest hot thing, about to take off with the consumer version of the Oculus Rift, HTC Vive et al… JavaScript can also do Virtual Reality.

Here’s one I made earlier: Virtual Reality fire safety training, using the Oculus Rift along with a Leap Motion controller so you can use your hands to interact with the scene:

<iframe src="https://player.vimeo.com/video/114942905?title=0&amp;byline=0&amp;portrait=0" width="540" height="304" frameborder="0" title="InteractiveVR-demovideo"></iframe>

It uses [Web VR](http://webvr.info/), a new JavaScript API that lets you integrate with the Oculus Rift or Google Cardboard, using your browser. It’s not in a mainstream browser release yet, but you can get hold of Firefox Nightly or a special build of Chrome to try it out (check out [mozvr.com](http://mozvr.com/)).

Essentially it extends the full screen API so you can launch your web page on the actual Head Mounted Display. It gives you the transformation you need to morph the view appropriately for the device. Plus the orientation data so you can move your scene around appropriately as the user turns their head.

Then [LeapJS](https://github.com/leapmotion/leapjs) provides the hand and finger position data, via a web socket data stream.

## Can you believe it?

![This cat can't believe it](/images/posts/2015-11-09-robots-vr-iot-cant-believe-its-javascript/i-cant-believe-it-cat.jpg)

From desktop apps, to virtual reality - JavaScript can do it all. Some of these examples might be on the bleeding edge; you might not be able to put some of this into production just yet. But I reckon it’s a safe bet that these technologies are up-and-coming, and by exploring them now, we can get ready for when they take off. All using our favourite language. One that no one can call a toy language anymore.... unless they simply mean that there’s so much to play with!

It’s a great time to be a JavaScript developer, don’t you think?
