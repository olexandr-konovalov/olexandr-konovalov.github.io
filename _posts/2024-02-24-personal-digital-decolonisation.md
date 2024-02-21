---
title: 'My personal digital decolonisation'
date: 2024-02-24
permalink: /posts/2024/02/24/personal-digital-decolonisation/
---

# My personal digital decolonisation

A year ago, I have asked my colleagues to stop calling me "Alex"
and use only "Olexandr", sharing with them an earlier version 
of this post. Today, I would like to share this story with you.

## Part 1: Historical background

I grew up in Zaporizhzhia, a regional centre on the Dnipro river, about
500 km South-East of Kyiv, and 50 km from the Enerhodar Nuclear Power
Plant, the largest in Europe. In this region Zaporizhian Cossacks
established their Sich in the 16th-18th centuries. But in my childhood
it was very much a Russian-speaking industrial city (however, you would
meet more Ukrainian speakers if you move just some 30 km into the
countryside).

My parents were born in Donetsk region. Although having no Russian
ancestry at all, we were a predominantly Russian-speaking family, even
although before the Second World War, my Grandmother worked as a school
teacher of Ukrainian. She used many Ukrainian words when she spoke
Russian, and she fluently spoke Ukrainian when she chose to. 

I studied Ukrainian language at school. Ukrainian was introduced from
Primary 2. The textbook was called "Ukrainian language". The Russian
language textbook for Primary 1 was called "Mother tongue". The teaching
in the majority of schools in Zaporizhzhia was in Russian. There were
only a couple of schools in the city with population about 800,000 in
which all teaching was in Ukrainian.

It was also possible to be completely exempt from studying Ukrainian. 
In my class, half of the pupils were exempt. My parents strongly 
believed that if one lives in Ukraine, one must learn Ukrainian, 
full stop. Once my Father said that at a parent council meeting. 
Apparently, after that he was never invited to the parent council again.

Eventually, after Ukraine gained independence, we became bilingual. In the
early 90s, we subscribed to several newspapers to read more texts in
Ukrainian. We watched TV in both languages. And now I can't even remember
whether we had some movies on videotapes in one language or another. We
started to insert some phrases or movie quotes in Ukrainian into a
conversation in Russian, just because they are more expressive and
better fit into the context. And although in the Zaporizhzhia National
University, where I worked after getting PhD, the majority of teaching
was still in Russian (only the official paperwork had to be in Ukrainian),
at some point I taught several undergraduate modules in Ukrainian. 

But now let's go back to my school years. First English lesson. Pupils
need to label their notebooks (or "copybooks", as they were called then)
with their personal details. I was told by the teacher to write my name
on it in English as "Alexander", and so did I. That sounded good enough.
So later in the 90s, when I started to use English to publish, communicate 
with other researchers by email or at conferences, I continued to use
"Alexander", even though I already had "Olexandr" in my Ukrainian
documents. That eventually shortened to "Alex", mainly for informal
communication - and it was faster to sign emails like that.

Eventually this started to slightly bother me. Why did I do that? What
am I trying to tell or to hide by this? If I have an original national
name, do I really need to adapt it to match a well known English
equivalent? But it seemed that it's too cumbersome and inconvenient to
change this back, and so I preferred to not to worry much about that.

But eventually I was becoming more and more concerned about this. 
I did not want to have a name which prompts false assumptions about my
background. For example, like assuming that one can see me for the first
time and try to talk to me in Russian without asking if I agree to that.
And then Russia started its full-scale invasion into Ukraine on February 24th, 2022.
I switched to "Olexandr" as my official name on that very day, starting
to change all email display settings and signatures. Next day,
Human Resources amended my "known as" name in their records. Within a few
hours, Pure – the Current Research Information System
([CRIS](https://en.wikipedia.org/wiki/Current_research_information_system)) used in St Andrews –
and [the University of St Andrews Research Portal](https://research-portal.st-andrews.ac.uk/),
both drawing from Human Resources database, were updated too. 
I have updated my display name
on a number of other accounts, such as e.g. [ORCID](https://orcid.org/),
[GitHub](https://github.com/), [Stackoverflow](https://stackoverflow.com/),
several Wordpress-based websites hosted at the University (e.g. research
groups of which I am a member), a dozen of [Slack](https://slack.com/)
workspaces, and also the office door. 
From time to time, I was discovering and updating other
relics such as e.g. my entries in bibliographic databases, professional
societies, journal editorial boards, etc. I have also eventually updated
my teaching materials, and never reused past lecture recordings
containing my old name ever since.

For a while it still seemed acceptable to keep using "Alex"
in informal communication. Although the name is derived from "Alexander",
nobody would ever call me "Alex" in Ukrainian or Russian. Thus,
I thought of it as of a kind of my British name, without negative
connotations. But then... Kharkiv. Enerhodar. Mariupol. Azovstal.
Bucha. Irpin. Kramatorsk. Kremenchuk. Izyum. Zaporizhzhia. Kyiv.
Bakhmut. Dnipro. Just impossible everything here. And after
each next missile strike, after each new Russian atrocity, I was less
and less keen to use the name "Alex" as a reminder that it is derived
from "Alexander".

Finally, I've accidentally met a colleague from another school, 
who knew me as "Alex" for about eight years, and discovered
that they didn't even realise all this time that I came to
St Andrews from Ukraine. That was the tipping point. Shortly
after, upon inspecting my technical options, I've decided that
I've had enough, and I need to fix this once and forever. 

That's what I have called **"my personal digital decolonisation"**.

## Part 2: Implementation details

First, I have fixed an annoying inconsistency with my usernames.
My departmental username at work was `alexk`. My GitHub username
was `alex-konovalov`. Thus, whenever I demonstrated something on my
computer while teaching, `alex` was popping up. To fix that, a new
account was created for me in the School of Computer Science, with the
name matching my University username. All content was moved over from
old account to new, and I had to deal with a few minor issues arising
from that change (updating some scripts; rebuilding some software;
generating new SSH keys to get rid of old email address included in
the old public key. After completely deleting the `alexk` account, 
I've realised that I've accidentally lost access to several Wordpress
websites hosted by the School of Computer Science, what was quickly
restored thanks to our school's system administrators.

Then I changed my username on my computer. One of the colleagues suggested to
either create a new account and gradually move things over, or rename
it following the instructions provided [here](https://support.apple.com/en-gb/HT201548).
After ensuring that I have two latest backups on two external drives,
I took a chance of doing the latter - it was a matter of minutes, and worked
seamlessly, with none of the standard apps broken! Some things that
needed a slight adjustment were paths to ignore for the time machine,
paths to VirtualBox VMs, some symbolic links and software builds, such
as e.g. GAP installation - but nothing was fundamentally broken.
While configuring this, I have also removed Russian keyboard layout
from all my devices.

I have continued efforts to change my name from "Alexander" to "Olexandr"
on preprint servers, bibliographic databases and other scientific services.
There is no standard way of doing that, and in each case it was a 
a unique experience, for example:

- [zbMATH](https://zbmath.org/) had to disambiguate a number of records
for people with the same surname as mine, previously attributed to the
same person (even with different full names or initials!).

- [Scopus](https://www.scopus.com/) happened to pick up two papers of
someone else named "Alexander Konovalov" and added them to my profile,
inferring wrong affiliation from their details in an offending way.
This was reported to Scopus, and was fixed by them within a couple of days.

- Association for Computing Machinery ([ACM](https://www.acm.org/)
was the only service that asked me to fill in and sign the official
name change form. After that, they have put this in the queue for
manual updates of their database. It took them nine months to update
my name, however, not only on my profile itself, but also on each
of the papers that I have published with ACM. In the meantime I
have published another paper under my real name, and they accidentally
created another profile with that one new paper. Thus, now they had
to merge both profiles, and set up a redirect from the new one to the
old one. Luckily, it took just a few hours for them to fix this.

- [DBLP](https://dblp.org/) still displays both my old and new name,
because "persons are identified in DBLP on basis of the persons name
string (optionally followed by a four digit number in case of several
authors in DBLP with the same name)".

- [MathSciNet](https://mathscinet.ams.org/mathscinet/)
had never replied to me, but swiftly updated my name as requested.

- Changing my name on [arXiv](https://arxiv.org/) did not update my
identifier `konovalov_a`, but at least arXiv allows me to hide that
by using an ORCID-based profile link, which does not include the name at all.

- [Figshare](https://figshare.com/) allowed me to update my account details.
That changed my name on each publication, but not in the list of 
publications shown under my profile. The problem was reported to 
Figshare and thanks to them, it was fixed within less than 12 hours after my report.

- For the On-Line Encyclopedia of Integer Sequences ([OEIS](https://oeis.org/)), 
I had to create a new account and then ask them to merge it with my old one.
After that, I had to manually edit the metadata for my mentions in the
OEIS entries to update the name.

Also, different things may happen with the names shown on the papers in
my profiles: they may be fully updated, or not updated at all, or only
updated for papers they publish themselves (like ACM), or not consistently
updated (like DBLP, who did this, but only for the most recent papers).

The rest of this post is related to my use of [GitHub](https://github.com/)
and [Zenodo](https://zenodo.org/) for developing and publishing research
software, and includes a lot of technical details. If you are not using
these platforms, please feel free to proceed to the last paragraph.
Otherwise, for [GitHub](https://github.com/), I've discovered that one
can actually change their GitHub username: see e.g.
[GitHub documentation](https://docs.github.com/en/account-and-profile/setting-up-and-managing-
your-personal-account-on-github/managing-personal-account-settings/
changing-your-github-username) and [another page here](https://mskelton.medium.com/my-experience-changing-my-github-username-
8414e1baa113). Most of my content was migrated seamlessly, including
all the repositories, submitted issues and pull requests, organisation
membership, and even unread notifications and gists. However, while
links to the repositories are automatically redirected, this is not
the case for links to `@username` mentions, and for websites hosted
on GitHub pages.

The next step was to update remotes in all repository clones which I
have locally. Since I have a dedicated directory to keep repository
clones, it was possible to do this in one go, with some shell scripting
and `sed` calls to find and fix all `.git/config` files. Another fix
required for the repositories which used the Git worktree extension:
some clones had a `.git` file setting up a `gitdir` variable with an
absolute path to the directory and had to be updated.

Of course, it is not possible to update everything. What's said on the
Internet, stays on the Internet. For example, old repository commits are
signed using my old name and email. I can possibly rewrite revision
history for private repositories, but it's too late to do this for
public repositories that may have forks and clones. Also, username change
distorts contributor statistics, showing two contributors instead of one.
GitHub instructions say "To attribute past commits to the new account,
add the email address you used to author the commits to the account you're
keeping", but one can't do that with old commits signed with
`alex-konovalov@users.noreply.github.com`. But I can live with that, and
using `.mailmap` file helped to fix this to some extent (it updates
reports by `git shortlog` but not the way how contributors are reported
on GitHub). On the other hand, following good software engineering practices,
such as making the code portable, avoiding full paths in the code
(as well as in the demos and documentation) paid off: there were only
several fixes of this kind necessary so far.

My GitHub username was then updated in the [Carpentries](https://carpentries.org/)
instructor database, and in the Journal of Open Source Software
([JOSS](https://joss.theoj.org/)) editorial system, both integrated
with GitHub. I have also updated the URL of my personal website, hosted on
GitHub pages, in multiple places, including GAP packages and other
projects to which I had contributed in the past. The GitHub search
functionality was very useful to discover occurrences of my old
username, about which I didn't even know in the past - for example, in
the repositories of Carpentries instructors with whom we were at some
point teaching together.

Then I looked at my software published on [Zenodo](https://zenodo.org/).
Because I mostly publish the software hosted in the accounts belonging
to GitHub organisations, and not in my personal one, that required only
two new releases to be made urgently (one of which from a repository
already migrated to another organisation, but never released from there).
The other projects were dealt with gradually. By now I have also re-released
all of the [GAP](https://www.gap-system.org/) packages to which I have
contributed, except one. In some cases, I had to fix contributor names
manually through the Zenodo interface, to avoid my name being duplicated
because of the new and old GitHub username.

I am determined to eventually update my details in as many places as I
can (certainly, some things are beyond reach, such as past conferences
and journal publications, posts in various forums, etc.). It's a tedious
process, but I am getting there.

## Conclusions

I have started with some historical background details.
If you are well informed about Ukraine, perhaps you haven't
read anything new - yet another personal story illustrating and
confirming what was already said many times by others (if you
haven't read it yet, I recommend this article by Sasha Dovzhyk:
[Mother Tongue: The Story of a Ukrainian Language Convert](https://newlinesmag.com/first-person/mother-tongue-the-story-of-a-ukrainian-language-convert/)).
Still, while we read about the increasing use of Ukrainian in
everyday life, I haven't seen anything specifically focused
on digital communications, especially in the context of academia.
This is why I have decided to give a detailed technical account
of what is involved in restoring Ukrainian spelling of my name
in various digital resources. I am also trying to argue that
using good research software engineering practices helped me
to reduce some efforts required. Finally, we can see that the
design limitations of various bibliographic databases, and the
lack of widespread adoption of persistent digital identifiers
provided to researchers by [ORCID](https://orcid.org/) makes
this process more complicated. 

I hope that this post demonstrates what _is_ possible, and may
be useful to anyone who changes their name in academia.
