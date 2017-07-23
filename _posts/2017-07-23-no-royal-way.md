---
title: 'There is no royal way in computational algebra'
date: 2017-07-23
permalink: /posts/2017/06/10/no-royal-way/
tags:
  - research software
---

This post is based on my answer to the question 
["Royal way to learn algorithmic/computational/computer algebra"](https://math.stackexchange.com/q/2353307/)
asked at Mathematics Q&A site by Jakob Werner. The questions asks for a book
recommendation, and then more specifically asks whether is it important to 
have a book focusing on one CAS explicitly; which CAS to decide for;
where does the programming experience come from; and how to check the 
written code is good.

The background described in the question is not uncommon - with
the growth of computational disciplines many researchers have to 
learn programming on the job, without any formal training during 
their degree studies. Below I will try to give some advice applicable 
to computational algebra. 

In principle, one could be a researcher in algorithms without doing any
actual programming. For example, one could study complexity of
algorithms and their asymptotic behaviour which will be beyond any
feasible computer implementations. On the other hand, programming skill
would be an advantage. It may help in understanding how to present
algorithms for their practical implementations, or to find worst case
performance examples; it may allow to play with things to check facts
and better understand the theory, and to find examples and
counterexamples. 

Now on the specific questions.

# Is it important to have a book focusing on one CAS explicitly?

No, it's not. A book dedicated to a particular CAS may not even exist in
a relevant area. Books are certainly important, but not only they.
Theoretical descriptions in the textbook could be quite high-level and
not hinting at subtle aspects of their practical implementation. Code
provided with textbooks may not run in the next version of the software.
It is also important to look at manuals, teaching materials, comments in
the code, or the code itself (provided the system is open source).

# Which CAS to decide for?

It depends on your area of research, on problem(s) which you'd like to
work on, and on availability on the relevant functionality in
appropriate CAS. An important factor is being open source. Besides CAS,
I recommend to learn at least one general purpose programming language,
for example Python. It has a large community and a plenty of teaching
materials available. If you may need to learn several CAS, it's better
to start to learn with the one which has a less steep learning curve,
seems more usable, has active community, accessible teaching materials,
etc. In no particular order, you may want to look at
[GAP](https://www.gap-system.org/),
[Macaulay2](http://www.math.uiuc.edu/Macaulay2/),
[SageMath](http://www.sagemath.org/),
[Singular](https://www.singular.uni-kl.de/),
and others.

# Where does the programming experience come from?

Reading existing code, preferably short and documented functions, is
useful, but it's not enough. As Brian Kernighan and Dennis Ritchie said
in the first edition of The C Programming Language in 1978, 
[_"The only way to learn a new programming language is by writing programs in it"_](https://www.artsy.net/article/ruse-laboratories-brian-kernighan).
You need to actually practice in writing your own code. Take some
algorithm and try to implement it from scratch. Check that the result
matches theory and/or existing implementation. Indeed, why not to try to
implement the Buchberger algorithm in Singular, or the orbit enumeration
algorithm in GAP? You will not have to re-implement everything since the
underlying computer algebra system will provide you with basic objects,
so you will start with some higher level, and will learn a lot about its
functionality in the process. Even if it will be not performing so well
as the native one, that would be a useful exercise.

# How to check if I have written good code?

I would reformulate it as "How to learn to write a good code" at try to
use some good practices from the beginning. You can find some useful
tips looking for reports from various "What makes good code good"
discussions on the Software Sustainability Institute website
[here](https://www.software.ac.uk/search/node?keys=what+makes+good+code+
good) (for example, see
[here](https://www.software.ac.uk/blog/2016-09-28-what-makes-good-code-
good-emcsr-2014) and
[there](https://www.software.ac.uk/blog/2016-10-07-what-makes-good-code-
good-mozfest)). I recommend to attend some [Software Carpentry
workshop](https://software-carpentry.org/workshops/) to learn more about
these practices. A typical workshop for beginners does not require prior
knowledge of the tools used, lasts about two days, and covers UNIX
shell, version control and programming with one of the languages (see
the list of lessons [here](https://software-carpentry.org/lessons/)). It
is "programming __with__ language", not "programming __in__ language",
since the emphasis is on general programming practices, being taught
with the help of a particular language. You can check for the future
workshops in your region
[here](https://software-carpentry.org/workshops/).

In addition, it's useful to follow mailing lists and Q&A sites for CAS
of your interest, get in touch with the community of its users and
developers (for example, at events like [GAP days](http://gapdays.de/)
or [SageMath days](https://wiki.sagemath.org/Workshops#Sage_Days) or at
training events like such [training schools](https://www.codima.ac.uk/schools/)). 
If the system has an issue tracker, perhaps some issues are labeled as 
newcomer-friendly (like we do in GAP
[here](https://github.com/gap-system/gap/issues?q=is%3Aissue+is%3Aopen+label%3Anewcomer-friendly)) so you may try to work on them and then get
some feedback from developers.
