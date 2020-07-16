---
title: The Future of the Web and What It Means for Education
slug: future-of-the-web-education
excerpt: What did the Future of Web Apps conference tell us about the future of education?
thumbnail: /images/posts/2015-02-26-future-of-the-web-education/thumb-to-the-future.jpg
date: 2014-10-15
tags: conferences, web, future-tech
layout: post.hbs
---

_Cross-posting of my [blog post at labs.pearson.com](http://labs.pearson.com/the-future-of-web-and-what-it-means-for-education/)_

--

What will the future have in store for the Web? Hundreds came
together in London a couple of weeks ago in the hope of finding out, at
the aptly titled [Future of Web
Apps](https://futureofwebapps.com/london-2014/) conference.
The talks were aimed at web developers, but the topics will end up
affecting everyone. So what were the major themes? And what does it mean
for education?

![To The Future!](/images/posts/2015-02-26-future-of-the-web-education/to-the-future.png)

<p class="caption">Credit: <a href="https://twitter.com/fowa/status/517319990882877441">Future Insights</a></p>

### Theme 1: More Powers for the Web

Those that create mobile applications will be familiar with a
long-standing “Native versus Web” mobile app debate. Native apps are
those that are developed for individual platforms, such as Apple’s iOS
or Google’s Android, and are generally downloaded via app stores. Web
apps can be accessed with a web browser just by typing a URL, selecting
a link, or tapping on its icon if you’ve bookmarked it.

Web apps are great because they have all the benefits of the World
Wide Web: being open and non-proprietary, universally linkable and able
to work on all kinds of devices. But users tend to prefer native apps.
The opening speaker, [Bruce
Lawson](http://www.brucelawson.co.uk/) from Opera,
[referenced a number of examples and
data](https://brucelawson.github.io/talks/2014/fowa/) that
reveal users spend significantly more time inside native apps than web
apps. Why is that?

**Offline first**

The biggest reason is probably because web apps don’t currently
work well offline. The [FT’s web
app](http://app.ft.com/) is a great exception to this
general rule, but it’s rare to see offline web apps because it’s
currently very tricky to do and there are lots of limitations.

Those who make our web browsers are working hard to change that.
By the end of this year, developers will be able to start using a new
feature called [Service
Workers](https://developer.mozilla.org/en-US/docs/Web/API/ServiceWorker_API)
which will give web apps lots of new powers to work offline (and more).
Websites will be able to be offline by default, and - like native apps -
update if and when there is a connection. It
should also allow websites to fetch updates in the background and notify
you when something important happens (with your permission).

Imagine students and teachers being able to continue interacting
with their school’s Learning Management System on their mobile phone,
when they no longer have a signal (for example, on an underground
train). These capabilities should be good for all of us, but it’s
especially good news for parts of the world where Internet connectivity
is sparse. As Bruce Lawson reminded us, “most of the world
doesn’t have connectivity”.

**Performance**

<span
id="docs-internal-guid-c924e1ec-132d-a80f-0b8a-d3dafebed142">Another
advantage you may have noticed for native apps is that they often feel
smoother as you scroll up and down or swipe around; they tend to have
snappier animations and transitions. Again, this is an area that the web
is trying hard to catch up on. Bruce informed us that for Blink - the
engine behind the Opera and Google Chrome browsers -
all of the priority for 2014 has been
performance on mobile. Opera are especially focusing on less-powered
phones, because “not everyone has the latest shiny iPhone”. This work
should help us to deliver better mobile web experiences to learners
around the world.

**Graphics and gaming**

The web is also becoming a platform for high-end gaming and
immersive, interactive experiences. Using a technology called
[WebGL](https://developer.mozilla.org/en-US/docs/Web/WebGL),
web apps can now provide near console-quality graphics. Up until now
WebGL has largely been the preserve of desktop demos, but support has
just arrived on iPhones and iPads with iOS 8, so we should see it start
to take off more on mobile now too.

If you would like to get a sense of what is possible, there is a
large set of WebGL demos here:
[<http://www.chromeexperiments.com/tag/webgl/>](http://www.chromeexperiments.com/tag/webgl/).
(Technically the site is for Chrome demos, but most of them should work
in various other browsers too. That’s the beauty of open
standards!).

If your mobile phone supports WebGL (you can test this by visiting
[get.webgl.org](http://get.webgl.org/)), then
look out for the mobile symbols indicating those that should be
mobile-friendly. A demo that I particularly like is [Racer
S](http://www.chromeexperiments.com/detail/racer-s/).

![Samsung Racer S](/images/posts/2015-02-26-future-of-the-web-education/samsung-racer-s.png)

<p class="caption">Credit: <a href="http://helloracer.com/racer-s/">Samsung Racer S</a></p>

**Audio**

We can also expect the web to make better use of audio in the
future; the topic of [Web
Audio](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)

- a powerful system for generating and controlling audio - came up in
  multiple talks.

If you’d like to test it out, here’s a demo that you can try in
Chrome on the desktop:
<http://www.jamwithchrome.com/>

**“Web+”**

Overall, these features should provide the Web with more of the
capabilities that users have come to expect from native apps. Bruce
termed this “Web+”. The best of the Web, plus the best of Native? It
should be a powerful combination…

### Theme 2: APIs everywhere

The future of the Web should also see a continuation of the
[rise of
APIs](http://thenextweb.com/dd/2014/03/28/api-economy/).
APIs are services that developers can use to help them build their
software. They might provide data, content, or functionalities that save
time and effort. For organisations that provide them, APIs can make
their services available to new audiences, and allow innovative new uses
that they might never have imagined.

With APIs becoming ever more ubiquitous, [Ian
Plosker](https://www.linkedin.com/in/ianplosker) said in
his talk that “Web 3.0 is about APIs. If software is eating
the world, APIs are eating software”.

In the world of education, this should lead to learning services
that are better integrated, more connected, and more open to
innovation.

### Theme 3: The Extensible Web

Another common theme was that we’re all responsible for defining
the future of the Web. It won’t simply be dictated to us by those who
make web browsers. The Web is based on open standards that we can all
contribute to.

However, in the past, browsers have sometimes provided features
that were too “magical”; they didn’t allow web developers enough control
and they ended up being limiting and frustrating. (The best example of
this is the previous attempt at solving the offline problem for the Web:
[AppCache](http://www.html5rocks.com/en/tutorials/appcache/beginner/)).

We heard that there’s a new approach called the
[Extensible
Web](http://extensiblewebmanifesto.org/). Browsers will
concentrate on providing comprehensive foundations, which developers can
build things on top of. Once developers start settling on approaches
that make the best use of those foundations, some of these additions may
also be standardised and built into the browsers themselves.

In practice, this should help the capabilities of the Web to
advance more quickly and more smoothly. This should be great for
developers and pay dividends for users of the Web too.

### The future of the Web? It’s bright

![Bright future](/images/posts/2015-02-26-future-of-the-web-education/bright-orange-web.jpg)

<p class="caption">Credit: <a href="https://www.flickr.com/photos/35378394@N03/3280622749/">CLUC, Flickr</a></p>

In the near future, watch out for websites that retain all the great
benefits of the World Wide Web, but also have more of the things we love
about native apps; for example, offline capabilities and console-quality
graphics. We can expect better quality, more mobile-friendly education
websites, and learning services that are more connected and more
flexible through the use of APIs.

And since the Web is open and extensible, we can all have our own say in
its future too.
