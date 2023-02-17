---
title: 'Publishing Software Carpentry lesson on GAP'
date: 2016-11-22
permalink: /posts/2016/11/22/publishing-software-carpentry-lesson-on-gap/
tags:
  - software carpentry
  - codima
---

Following the [2nd CoDiMa training school](http://www.codima.ac.uk/school2016/), 
I have published the 
[Software Carpentry lesson on GAP](http://olexandr-konovalov.github.io/gap-lesson/) 
via Zenodo: see [10.5281/zenodo.167362](http://doi.org/10.5281/zenodo.167362). 
The lesson is based on the problem of determining an average order of an element 
of a finite group, and finding examples of groups for which the average order of 
their elements is an integer. First I have heard about this problem when Steve 
Linton used it in a talk in order to quickly demonstrate some GAP features to a 
general scientific audience. I have tried to expand on it in my talk in Newcastle 
in May 2015 (see the blog post 
[here](http://www.codima.ac.uk/2015/07/01/average-order-of-group-elements-a-demo-of-test-driven-development-in-gap/)), 
and decided to proceed with it.

Indeed, the problem of determining an average order of the element of the group 
is simple enough to not to distract learners too much from the intended learning 
outcomes of the lesson. An undergraduate algebra course is sufficient for its 
understanding. Moreover, those not familiar with the group theory still should 
be able to follow the lesson just by grasping the idea that there is a mathematical 
structure called group, and we need to find an average value of a certain numerical 
parameter associated with each element of it. On the other hand, those with 
sufficient theoretical background will hopefully enjoy seeing how the initial 
naive implementation is being refined several times during the lesson, and how 
theoretical insights are giving much more significant advances than minor code 
optimisations or just getting more cores.

The lesson starts with formulating the problem of finding examples of groups 
such that the average order of their element is an integer. It first explains 
how to work with the GAP command prompt, demonstrates some basic language 
constructions and explains how to find necessary information in the GAP help 
system. At this point using the command line we establish a rough prototype of 
the code to compute an average order of a group, and tried several examples, 
none of them yielding an integer.

Next, it discusses that the command line usage is good only for rapid prototyping, 
and explains how to create GAP functions, place them into a file, and read that 
file into GAP. After that, the initial implementation is used to create a 
regression test: GAP runs it by comparing the actual output with the reference 
output, and will fail the test in case of any discrepancies. Testing the code 
is a topic that usually escapes beginners' attention, and I am really excited 
about managing to cover it as a part of the introductory GAP lesson. I explain 
the "make it right, than make it fast" paradigm, and show how to create and run 
regression tests in GAP after the first naive implementation is available. To 
demonstrate test failures, I deliberately mixed up function names to break the 
test, and it was a real pleasure when the audience pointed that out before I 
even managed to re-run the test and demonstrate that it failed.

Having the improved and tested implementation, we start systematic search for 
finite groups with an integer average order of an element using the 
[GAP Small Groups Library](http://www.gap-system.org/Packages/sgl.html) which 
contains, among others, all 423 164 062 groups of order at most 2000 except 1024. 
At the same time, the lesson introduces modular programming and shows how one can 
design a system of functions to perform the search in a way that one could re-use 
most of the code and only develop a new function to test a single group to deal 
with another search problem. Then the first interesting example (a group of order 
105 such that the average order of its elements is 17) is discovered! The next 
obstacle is to check all 56092 groups of order 256, however, a short theoretical 
observation shows that we can exclude groups of prime power order from the search, 
as they will never have an integer average order of an element. After modifying 
the code to skip such orders, the search continues, and then another example 
(a group of order 357) is found. Discovering another known group with this property 
is left as one of the exercises.

The lesson finishes with explaining how the knowledge about the object can be 
stored in it. For example, once the average order of an element of a group is 
calculated and stored in the group, it can be next time retrieved at zero cost, 
avoiding redundant calculations.

Of course, it is not possible to cover everything in a several hours long course, 
but it fits really well into the week-long CoDiMa training school like 
[this](http://www.codima.ac.uk/school2016/). It prepares the audience to hear 
about more advanced topics during the rest of the week: debugging and profiling; 
advanced GAP programming; GAP type system; distributed parallel calculations; 
examples of some algorithms and their implementations, etc. Also, staying for 
the whole week of the school, everyone has plenty of opportunities to ask 
further questions to instructors.

What next? So far I am only aware that it has been taught twice (by myself) at 
two annual 
[CoDiMa training schools in computational discrete mathematics](http://www.codima.ac.uk/schools/). 
I can surely teach it myself, but is it written clearly enough to be taught by others? 
Is it possible for the reader to follow it for self-studying? Is there any 
introductory material missing, or is there an interest in having more advanced 
lesson(s) on some other aspects of the GAP system? If you would like to 
contribute to its further development, issues and pull requests to its repository 
on [GitHub](https://github.com/olexandr-konovalov/gap-lesson) are most welcome! Also, 
we invite collaborators interested in developing a lesson on 
[SageMath](http://www.sagemath.org/): please look at 
[this repository](https://github.com/olexandr-konovalov/sage-lesson) and add a 
comment to [this issue](https://github.com/olexandr-konovalov/sage-lesson/issues/1) 
if you’re interested in contributing.