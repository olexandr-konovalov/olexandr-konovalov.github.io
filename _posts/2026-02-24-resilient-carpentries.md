---
title: 'Resilient Carpentries: running a workshop in times of the war'
date: 2026-02-24
permalink: /posts/2026/02/24/resilient-carpentries/
---

On 20-21 January 2026 the [Ukrainian Carpentries Community](https://ukrainian-carpentries.github.io/) 
run the first ever
[Carpentries workshop in Ukraine](https://ukrainian-carpentries.github.io/2026-01-20-dnipro-online/),
making Ukraine the 72nd country in the world hosting The Carpentries workshops. 

This workshop was a part of the
[Winter School in System Analysis and Artificial Intelligence](https://sau.nmu.org.ua/ua/school_analysis.intelligence/2026/winschool26.php),
organised by the [Department of System Analysis and Control](https://sau.nmu.org.ua/ua/)
of [Dnipro Polytechnic](https://nmu.org.ua/).

Dnipro Polytechnic is located in the centre of the city of Dnipro. Dnipro is the fourth largest city in Ukraine, situated just 70 km north from my home city Zaporizhzhia. 
I visited Dnipro many times, travelling by car, bus, train, plane and even by a hydrofoil boat.
But since the beginning of russia's full scale invasion in Ukraine - exactly 4 years ago today - both Dnipro
and Zaporizhzhia turned into frontline cities.
The air raid alerts and electricity blackouts became regular events. 
Still, in such conditions under relentless russian attacks, 
Ukrainian academics and students gather for these winter schools, and not for the first time - this is
already the 3rd of the series, with the first one held in January 2024
(see the list of all schools [here](https://sau.nmu.org.ua/ua/school_analysis.intelligence/schoolregulation.php)).
I admire their resilience, and it was an honour for me to get involved.

This wasn't our first collaboration: in January 2024, 
the Ukrainian Carpentries Community already run a pilot [Git training](https://ukrainian-carpentries.github.io/trainings)
for the initial school of the series. That was the first Git training we conducted using 
the [Ukrainian version of the Version Control with Git lesson](https://ukrainian-carpentries.github.io/git-novice/).
Now in 2026 the Winter School organisers were inviting us to do the Git training again, and we met at one 
of [our monthly calls](https://hackmd.io/drNoAPc5QpqH4nWm71YJkg?view) in November to discuss the possibility of organising
a full Carpentries workshop, teaching not just Git, but also UNIX shell and some programming language. To support this,
we already translated all episodes of UNIX shell lesson, large part of the Python lesson, and a workshop template, all listed on [our webpage](https://ukrainian-carpentries.github.io/).

However, we have discovered that the majority of participants are expected to be undergraduate students of computer science
or electrical engineering degrees who are already well familiar with Python. 
Therefore, teaching Python does not seem to be a wise approach. 
Luckily, a few months before a group of translators in the National University of Ostroh Academy (twinning
partner of the University of St Andrews) started to translate the [R for Social Scientists](https://ukrainian-carpentries.github.io/r-socialsci/) lesson. 
Dr Yurii Kleban, who coordinated the work of two Ostroh Academy students
(Daria Stehnii and Bohdana Strelyuk), is an R expert who has previously been helping at our training and 
witnessed The Carpentries pedagogical approach in practice. He enthusiastically volunteered to prepare and teach R at our workshop at the Winter School, and the translators of the R lesson
 volunteered to intensify their translation and reviewing efforts. 
 They translated 100% of the text, and thanks to them, by the time of the workshop we were able to render the translated lesson website with nearly 60% of the translations reviewed, approved, and visible online.

Planning to run a workshop under air raids and blackouts required us to think of many things not covered by [The Carpentries Handbook](https://docs.carpentries.org/).

First, we have decided to start the Carpentries part of the Winter School as early as possible in the week, and suggested that instructors and helpers should reserve, if possible, some additional time after the two initial days of the workshop, just in case we need to reschedule some sessions.

All sessions were recorded in the Microsoft Teams channel of the Winter School, so that participants may catch up later if they were forced to skip some sessions because of an air raid alert or problems with Internet connection. Some of the recordings were later published [here on YouTube](https://www.youtube.com/@depSAaC_NTUDP/videos).

The School organisers wanted to provide certificates of attendance to participants. Of course, in these conditions this cannot be based solely on their presence in online sessions, and hence the learners were asked to provide some evidence of following the content of the workshop. For example, for Day 1 the evidence was the URL of the public repository created following the Git lesson. Thus, learners missing the session could have followed the recording on their own and submit the result.

Some participants of the live sessions were unable to join us from their computers during electricity blackouts, and were joining the call from mobile devices. In particular, by the time of the collaborative exercise at the end of the Git lesson, only about 10 learners were able to stay on their computers. Therefore, we have decided to organise breakout rooms in a way that each room has two learners who use computers, and everyone else is watching what are they doing from a mobile device, and can try to simulate and merge conflicts in their own time later. 

We also had to discuss what would happen if Yurii loses power during his teaching of R on Day 2. Yurii said that in case of a blackout he would be able to stay connected and teach for another hour using his reserve power supply. This would give us some time to decide what to do next - either he could relocate during the break, or I can jump in and teach from where he stopped (because we are using the standard Carpentries lesson which provides interoperability between instructors). Yurii also had his own slides prepared for teaching, so if anything happened, perhaps he would also be able to demonstrate them from a mobile device. Luckily, his teaching went without disruptions.

There was also an additional question about installation instructions for the UNIX shell and Git for Windows.
Our [translated workshop template](https://ukrainian-carpentries.github.io/workshop-template/)
still suggests to use Git Bash and not the Windows Subsystem for Linux v2 (WSL2)
which is the current default option for the
[English workshop template](https://carpentries.github.io/workshop-template/). 
We simply had not managed yet to catch up with all template updates (while we use [crowdin.com](https://crowdin.com/) to translate the lessons, the template was translated straightforwardly in a fork of the [workshop template repository](https://github.com/carpentries/workshop-template/)). 
However, in my opinion going with Git Bash was easier, and we would not have capacity to provide support for WSL2 installation remotely. See also this [GitHub issue](https://github.com/carpentries/workshop-template/issues/887) for the discussion started by Sarah Stevens.

As a result, we had 46 registered participants, representing 9 universities from 6 cities. 
Day 1 was UNIX shell and Git; Day 2 was Programming in R. Overall, the workshop went well. 
I would like to thank everyone: the learners for their resilience and perseverance; 
our helpers (Roman Ilyushin, Volodymyr Kharchenko, Iryna Raievska, Maryna Raievska,
Veronika Shevchenko, Bohdana Strelyuk), the majority of which also took part
in the translation work and were delighted to see the outcomes of their efforts in practice; 
local organisers (Olha Stanina and Svitlana Us); 
and my fellow instructor Yurii Kleban. Each of you helped to make it happen!
