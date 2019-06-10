---
layout: post
title: "Test Driven Development at a Code Retreat"
subtitle: "Learning to write unittests while pair programming."
date: 2019-06-10 10:45:13 +0200
background: '/img/posts/2019-06-10.jpg'
---

What an incredible privilege to live near a city where volunteers give up their Saturdays to help others improve their skills!

On Saturday, 8 June, I participated in the [Cape Town Software Developers'](https://www.meetup.com/Cape-Town-Software-Developers/)
[Code Retreat](https://www.meetup.com/Cape-Town-Software-Developers/events/261742542/). I had no idea what to expect there, but 
looking at the questions and responses on their Meetup page, I noticed that the organisers - specifically Nigel Basel - were very
friendly and tolerant of newcomers to the community. In the week leading up to the Code Retreat, I thought about what I would like 
to learn, and came to the conclusion that I haven't spent anytime on TESTING yet but have had it on my to-do list for some time now. 
It would be great if I could learn some testing...

## The Venue

The event took place at [Kelvin Corner](https://kelvincorner.com/) in Woodstock, Cape Town, and we were received enthusiastically 
by co-owner Rob Weidner. Kelvin Corner is a new co-working space with a lovely setup. 
There are private offices, meeting spaces, a wonderful patio with a full view of Table Mountain, wifi, and great coffee and food.

## The Hosts, Organisers, and Sponsor

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">This event is<br>Facilitated by Alain &amp; Nigel<br>Hosted by :David Campey &amp; John Mupetami<br>Hosted at: Kelvin Corner<br>Organised by Coder:LevelUp<br>Sponsored by Investec <a href="https://t.co/Xjxx2FMlQV">https://t.co/Xjxx2FMlQV</a></p>&mdash; John(y) Mupetami (@Johnmupetami) <a href="https://twitter.com/Johnmupetami/status/1135881504578572288?ref_src=twsrc%5Etfw">June 4, 2019</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## The Participants

There were between 30 - 40 developers from various career stages, backgrounds, and 
most importantly programming preferences. 

## The Problem

We were introduced to [Conway's Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life). A fantastic problem with a few simple rules which we had to program.

<iframe width="560" height="315" src="https://www.youtube.com/embed/CgOcEZinQ2I" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## The Schedule
### Pair up, 45 min coding, 15 min retro, 10 minute break, repeat x 5

Alain and Nigel introduced us to the plan for the day after our 8am coffee. We also got to introduce ourselves shortly. 

Low and behold! I was going to learn about testing. The whole day was about
[Test Driven Design](https://www.freecodecamp.org/news/test-driven-development-what-it-is-and-what-it-is-not-41fa6bca02a2/)! 
We kicked off with an introduction to test driven design and pair programming. The hosts explained what the benefits of test
driven design is and how we were going to work in pairs to start building a product. We would try to find a mate who were 
interested in the same programming language or wanted to work on a similar aspect of the problem even if two people were used
to working in different programming languages. Most of all we were supposed to **get a feeling for the rhythm of test driven 
development rather than getting a product out** at the end of the day.

At every round we were introduced to new constraints for the coding session. In one round for example, one person had to 
write the test, and the second person had to write the code that would pass the test.

After every coding session we would head outside to the patio overlooking Table Mountain, and talk about what we learned, what
we found surprising or hard, and how far we came. It was incredibly insightful to hear how highly experienced developers were
comfortable to talk about what they didn't expect, how they were making assumptions about the problem that was tripping them
up, how they learned from their pairing buddies, and more. It was also great that new developors could contribute and participate
equally.

## My Experiences

I learned so much from everyone there! 

- There are developer communities where developers are kind to one another.
- Keegan showed me how to set up my test environment and we also checked some references to make sure I could find relevant information online again after the day to continue learning.
- With Matei I experienced the power of a good text editor/IDE. WOW!
- Sphe reminded me that we were there to learn and that I should stop being stubborn and as for help when I am stuck.
- David took it really slow from the start again and not only showed me the process of building up the tests (and especially the
beauty of the red/green cycle) but also reminded me that it's okay to go back to the documentation if some fundamental 
syntax was eluding me (like constructing classes and everything that goes with it).
- De Wet and I chatted a bit about how to include testing in programming for data analysis rather than software development.
- I had a great conversations with Abed about his studies, my planned studies, and more.
- Afterwards we had some great conversations about MineCraft, coding for children, women in tech, and more.

## Thanks to Organisers, Hosts, Sponsor, and Fellow Participants!

At the end we had a Closing Circle session where everyone could report back on their experiences:
### What did you find surprising?
I was surprised about how kind the developers were to each other throughout the day, while they were coding, during the retro
and during informal conversation over lunch or breaks. I've been exposed to some rather harsh developer environments in the past 
few years, but what I found here was respectful people excited to learn from each other and grow.

## What did you learn?
Most of all I learned where to start with writing unit tests in Python. I absolutely loved the processs of test driven design
as it was presented to us and as we practiced it during the day.

## What will you do differently on Monday?
I said that I'll fix up a [script that I have written for data analysis](http://datascentable.org/2019/06/04/hackday.html)
to include at least one test in it. I have read a bit about including tests in Jupyter Notebooks (in which this script was written) and
have decided to rather move forward and start the whole process of test driven design in the next script that I write for contributing to 
the [Metabolism of Cities](https://metabolismofcities.org/) project for which I recently became a data contributer. I'll write about
that script and the experience of employing test driven design in a next blog post.

