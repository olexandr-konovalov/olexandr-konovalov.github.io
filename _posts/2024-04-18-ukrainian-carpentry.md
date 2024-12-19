---
title: 'Software Carpentry for Ukraine: status update'
date: 2024-04-18
permalink: /posts/2024/04/18/ukrainian-carpentry/
---

This is an overview of the current state of the project of translating
Software Carpentry lessons into Ukrainian language. It accompanies the 
[slide of my lightning talk](https://zenodo.org/records/10995105) at the
[Collaborations Workshop 2024](https://www.software.ac.uk/workshop/collaborations-workshop-2024-cw24).
It is also [republished on The Carpentries website](https://carpentries.org/blog/2024/05/software-carpentries-translation-efforts-in-ukrainian/),
but without the updates at the end of this post.

This project was initiated by me in summer 2022, and after getting some initial
practice with the translation toolchain in a small team,
in 2023 we have invited St Andrews students to join us under the 
[StARIS](https://www.st-andrews.ac.uk/students/academic/internships/staris/)
and [STEP](https://olexandr-konovalov.github.io/posts/2023/04/24/carpentries-step-up/)
programmes, and also [invited external contributors](https://olexandr-konovalov.github.io/posts/2023/03/28/carpentries-translation/).
By now the project involves 16 members from 6 locations, interacting via
a Slack workspace and regular monthly video calls.

We very much appreciated the ability to access the existing Carpentries translation
infrastructure, which used the [Transifex](https://www.transifex.com/)
platform for collaborative translation (personal thanks to David Pérez-Suárez
for all the help with setup and rendering lessons). A pilot training in
version control with Git in Ukrainian took place at
[Research Software Camp: FAIR Software](https://www.eventbrite.co.uk/e/git-version-control-in-git-tickets-650799186887) in June 2023,
with [its recording available on YouTube](https://www.youtube.com/watch?v=RAaROljwy38).
However, while the training was delivered in Ukrainian, at that time
we still did not have a proper online version of the Git lesson in Ukrainian.

Continuing translation, by the start of 2024 we achieved further progress
with a few more lessons, most notably with the following four:
* [The Unix Shell](https://swcarpentry.github.io/shell-novice/)
* [Plotting and Programming in Python](https://swcarpentry.github.io/python-novice-gapminder/)
* [Introduction to R for Geospatial Data](https://datacarpentry.org/r-intro-geospatial/)
* [Programming with GAP](https://carpentries-incubator.github.io/gap-lesson/)

The image below shows the level of completion of the initial translation (green)
and its review (blue) for each lesson as it was in January 2024, just before we
started migration to another collaborative platform called [Crowdin](https://crowdin.com/).

![Transifex translation completion - January 2024](https://olexandr-konovalov.github.io/images/Transifex-2024-01-31.png)

The [Crowdin](https://crowdin.com/) platform offers better opportunities
for us, both in terms of its functionality and of the translation workflow,
with semi-automated rendering of the online version of the translated lesson
requiring only to press a few buttons in Crowdin and GitHub. In addition,
it will be already adapted to the most recent template of the Carpentries
lessons, called [Workbench](https://carpentries.github.io/workbench/). 
As soon as all the needed setup will be implemented in the Carpentries
Crowdin organisation, we expect to provide online Ukrainian versions of
all translated lessons very soon. 

Right now we are ready to organise stand-alone trainings
in using version control with Git, and have already conducted a few ones.
The first online one in January 2024 was at the Winter School in System Analysis
and AI at Zaporizhzhia & Dnipro Polytechnics. For the first time, it
used the online lesson "Контроль версій за допомогою Git" (Version control
with Git), available at
[https://ukrainian-carpentries.github.io/git-novice/](https://ukrainian-carpentries.github.io/git-novice/),
and already using the new Workbench template
(you can compare it with the [English version here](https://swcarpentry.github.io/git-novice/)).

This became possible thanks to the Bioconductor team for letting us temporarily use their
Crowdin account, and personally to Joel Nitta for exporting translations
from Transifex to Crowdin on a very short timescale. After the export, we
only had to manually migrate some text fragments, not picked up by the automated
procedure, and then approve all the remaining translations.

In March, another training was organised for the Ostroh Academy
(University of St Andrews' partner under the UK-Ukraine Twinning Initiative).
That was a hybrid event, with helpers present in the room
to respond to pink sticky notes when learners needed help (for the news item and photos, see
["В Острозькій академії відбувся весняний семінар комп'ютерної школи"](https://www.oa.edu.ua/ua/info/news/2024/06-03-01)).

Furthermore, Zaporizhzhia Polytechnic is now using the Git lesson as a
foundation for one of the courses for the PhD students of the Department
of System Analysis and Computational Mathematics.

The next goal is having available online a full set of lessons for a standard
Python, R or GAP based Software Carpentry workshop. Once at least one of these
three lessons on programming will be completed, we would be ready to organise a full scale
Software Carpentry workshop (i.e. involving programming, UNIX shell and Git lessons)
for Ukrainian-speaking audience, and start to build a community of the Carpentries
instructors in Ukraine (translation of the instructor training curriculum is already
in progress). Please contact me if you're interested to learn more and take part
in this initiative!

**Update 1:** [2024-06-16] The Carpentries Workshop Template has been
translated as well: [https://ukrainian-carpentries.github.io/workshop-template/](https://ukrainian-carpentries.github.io/workshop-template/).

**Update 2:** [2024-06-25] I have a short talk about this, with some most
recent updates, at the SSI Fellows Community Call on 11th June 2024. Its
recording is available [here](https://www.youtube.com/watch?v=kyp8B3VNapM).

**Update 3:** [2024-11-18] In summer 2024 we run a STEP project
"Adding Ukrainian translations to Glosario - an open source glossary of terms used in computing and data science"
(you can find its description at the bottom of
the [STEP 2024 page](https://www.st-andrews.ac.uk/ceed/summer-enterprise-programme/)).
It resulted in translating about 15% of Glosario terms into Ukrainian, available at
[https://glosario.carpentries.org/uk](https://glosario.carpentries.org/uk/). If you
are interested in contributing to Glosario, please see the documentation at
[https://github.com/carpentries/glosario](https://github.com/carpentries/glosario)
and ask me if you need any help to begin.
