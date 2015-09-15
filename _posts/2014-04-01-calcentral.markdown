---
layout: default
modal-id: 1
title: CalCentral
date: 2014-04-01
img: calcentral.png
alt: image-alt
project-date: April 2014
client: Berkeley Law School
client-url: http://law.berkeley.edu
source-url: https://github.com/ets-berkeley-edu/calcentral
category: Web Development

---
Until only recently, Berkeley students have juggled a number of websites to
access their student information: grades and registration information were
hosted on one website, financial aid found on another, and yet another site
existed for class schedules and assignments. In 2014, Berkeley ETS introduced
[CalCentral][calcentral], a new online portal designed to combine the
information from the multitude of older websites and present it in a single
location.

Over the summer of 2014, I worked with the Berkeley Law School to develop a
Law student-specific experience for their students when they accessed
CalCentral. Though CalCentral worked wonderfully well for the majority of
Berkeley students, Law School users had a number of different needs that were
going unmet. Through the changes I implemented, they would be presented with
information drawn from the Law School's internal APIs, see entirely separate
external links, and receive more relevant news and updates.

CalCentral was developed using [Ruby on Rails][rails] and [AngularJS][angular],
neither of which I had worked on prior to that summer. This made familiarizing
myself with the existing codebase quite intimidating at the start, especially
with the added complexity of understanding the multitude of different Berkeley
APIs being called in various sections of the application. But learning to work
with these tools and seeing my code eventually incorporated into such a
large-scale project was incredibly rewarding.

[calcentral]: https://calcentral.berkeley.edu/
[rails]: http://rubyonrails.org/
[angular]: https://angularjs.org/
