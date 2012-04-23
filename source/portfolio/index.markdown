---
layout: page
title: "Past Project Portfolio"
comments: false
sharing: true
footer: true
---

The following is a list of some of the projects I've worked on that I'm allowed to publicly talk about.
The list comprises projects in fields such as iOS development, medical visualization, custom multi-touch installations and open source.


iOS
---

#### Medical Classrooms

For a client in California, I created an iOS app for medical classrooms.
It performs real-time, three-dimensional rendering of medical volume data (CT, MRI) and allows for extensive
digital interactivity between multiple instances of the app on the network (students and teachers are all equipped with iPads).

{% img /portfolio/interface.png %}
{% img /portfolio/users.png %}
{% img /portfolio/classroom.jpg %}


Copyright 2012 Loma Linda University. Patent pending. Soon to be on the AppStore.

#### Python on iOS

As part of a research project, I've [worked on](https://github.com/dennda/python-for-iphone) porting the [Python](http://python.org) programming language{% fn_ref 1 %} to iOS.
It allows using Python in any Objective-C application and **does not** require a jailbreak. Others have used this approach to great extent in their apps (which are available on the AppStore).


Medical Visualization
---------------------

I've done some work in the field of medical visualization. The main challenge in this field is to make vast sets of data visually comprehensible.

One such attempt is shown below, where I wrote an OpenGL-based program to help neurosurgeons understand nerves in the human brain better.
The input to the program is a diffusion MRI scan of a person's brain. You then select a region of the brain where you want to see the fibers,
e.g. when planning a surgical removal of a tumor, in which you don't want to damage brain nerves that are invisible once you 'cut a patient open'.

#### Before
{% img /portfolio/primitive_fibers.png %}

#### After
{% img /portfolio/nice_fibers.png %}
{% img /portfolio/nice_fibers_ao.png %}

I have co-authored two papers on this and related visualization techniques:

 * "Advanced Line Visualization For HARDI", Bildverarbeitung f&uuml;r die Medizin (BVM) (2012)
 * "An Exploration and Planning Tool for Neurosurgical Interventions", IEEE Visualization Contest 2010, Honorable Mention


Multi-Touch
-----------

#### Medical Demo Installation

Another project I created has a medical component, too, but is more user interaction centric.
It allows medical data to be displayed on custom multi-touch installations.
This can be used in medical meetings, or for doctors to explain and demonstrate things to patients.
The project was submitted to a CompVis competition and was awarded the first prize (30 projects total).

{% img /portfolio/mark_bonetouch.JPG %}
<iframe src="http://player.vimeo.com/video/13282333?title=0&amp;byline=0&amp;portrait=0&amp;autoplay=0" width="200" height="112" frameborder="0" webkitAllowFullScreen mozallowfullscreen allowFullScreen></iframe>


#### Markerless Object Recognition

The following is the result of a relatively short (five week) research & development project for a company in Paris.
The goal was to allow custom objects to be recognized without the use of active or passive markers, based solely on an object's contour.

<iframe src="http://player.vimeo.com/video/19209891?title=0&amp;byline=0&amp;portrait=0&amp;autoplay=0" width="200" height="150" frameborder="0" webkitAllowFullScreen mozallowfullscreen allowFullScreen></iframe>


Open Source
-----------

I've also founded or contributed to a number of open source projects for custom multi-touch installations,
such as [Movid](http://movid.org), [Kivy](http://kivy.org), [PyMT](http://pymt.eu), as well as web development,
such as [Zine](http://www.pocoo.org/projects/zine/#zine) and [MoinMoin](http://moinmo.in), and well-known projects such as [Ubuntu](http://ubuntu.com).

I wrote several articles for the (commercial) UNIX print magazine [freeX](http://www.cul.de/freex.html) as an independent author.

I was accepted and successfully participated four consecutive times in Google's annual SoC program, most recently for the [Natural User Interface Group](http://nuigroup.com).


{% footnotes %}
  {% fn More specifically, version 2.7 of the CPython interpreter. %}
{% endfootnotes%}
