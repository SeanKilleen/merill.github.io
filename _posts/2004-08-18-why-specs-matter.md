---
id: 281
title: Why specs matter
date: 2004-08-18T14:33:01+00:00
author: Merill Fernando
layout: post
guid: /post/2004/08/Why-specs-matter.aspx
permalink: /2004/08/why-specs-matter/
dsq_thread_id:
  - "78579743"
categories:
  - Inspiration
---


<div class=Section1>

<p class=MsoNormal><span style='font-size:10.0pt;font-family:Verdana'>Most
developers are morons, and the rest are assholes. I have at various times
counted myself in both groups, so I can say this with the utmost confidence.</span></p>

<p class=MsoNormal><span style='font-size:10.0pt;font-family:Verdana'>&nbsp;</span></p>

<p class=MsoNormal><b><span style='font-size:10.0pt;font-family:Verdana'>Assholes</span></b></p>

<p class=MsoNormal><span style='font-size:10.0pt;font-family:Verdana'>Assholes
read specs with a fine-toothed comb, looking for loopholes, oversights, or
simple typos. Then they write code that is meticulously spec-compliant, but
useless. If someone yells at them for writing useless software, they smugly
point to the sentence in the spec that clearly spells out how their horribly
broken software is technically correct, and then they crow about it on their
blogs.</span></p>

<p class=MsoNormal><span style='font-size:10.0pt;font-family:Verdana'>&nbsp;</span></p>

<p class=MsoNormal><span style='font-size:10.0pt;font-family:Verdana'>There is
a faction of assholes that write test cases. These people are good to have
around while writing a spec, because they can occasionally be managed into
channeling their infinite time and energy into finding loopholes before the
spec is final. Unfortunately, managing assholes is even harder and more
time-consuming than it sounds. This is why writing good specs takes so long:
most of the time is frittered away on asshole management.</span></p>

<p class=MsoNormal><span style='font-size:10.0pt;font-family:Verdana'>&nbsp;</span></p>

<p class=MsoNormal><b><span style='font-size:10.0pt;font-family:Verdana'>Morons</span></b></p>

<p class=MsoNormal><span style='font-size:10.0pt;font-family:Verdana'>Morons,
on the other hand, don&#8217;t read specs until someone yells at them. Instead,
they take a few examples that they find &#8220;in the wild&#8221; and write
code that seems to work based on their limited sample. Soon after they ship,
they inevitably get yelled at because their product is nowhere near conforming
to the part of the spec that someone else happens to be using. Someone points
them to the sentence in the spec that clearly spells out how horribly broken
their software is, and they fix it.</span></p>

<p class=MsoNormal><span style='font-size:10.0pt;font-family:Verdana'>&nbsp;</span></p>

<p class=MsoNormal><span style='font-size:10.0pt;font-family:Verdana'>Besides
the run-of-the-mill morons, there are two factions of morons that are worth
special mention. The first work from examples, and ship code, and get yelled
at, just like all the other morons. But then when they finally bother to read
the spec, they magically turn into assholes and argue that the spec is
ambiguous, or misleading in some way, or ignoreable because nobody else
implements it, or simply wrong. These people are called sociopaths. They will
never write conformant code regardless of how good the spec is, so they can
safely be ignored.</span></p>

<p class=MsoNormal><span style='font-size:10.0pt;font-family:Verdana'>&nbsp;</span></p>

<p class=MsoNormal><span style='font-size:10.0pt;font-family:Verdana'>The
second faction of morons work from examples, ship code, and get yelled at. But
when they get around to reading the spec, they magically turn into advocates
and write up tutorials on what they learned from their mistakes. These people
are called experts. Virtually every useful tutorial in the world was written by
a moron-turned-expert.</span></p>

<p class=MsoNormal><span style='font-size:10.0pt;font-family:Verdana'>&nbsp;</span></p>

<p class=MsoNormal><b><span style='font-size:10.0pt;font-family:Verdana'>Angels</span></b></p>

<p class=MsoNormal><span style='font-size:10.0pt;font-family:Verdana'>Some
people would argue that not all developers are morons or assholes, but they are
mistaken. For example, some people posit the existence of what I will call the
&#8220;angel&#8221; developer. &#8220;Angels&#8221; read specs closely, write
code, and then thoroughly test it against the accompanying test suite before
shipping their product. Angels do not actually exist, but they are a useful
fiction to make spec writers to feel better about themselves.</span></p>

<p class=MsoNormal><span style='font-size:10.0pt;font-family:Verdana'>&nbsp;</span></p>

<p class=MsoNormal><b><span style='font-size:10.0pt;font-family:Verdana'>Why
specs matter</span></b></p>

<p class=MsoNormal><span style='font-size:10.0pt;font-family:Verdana'>If your
spec isn&#8217;t good enough, morons have no chance of ever getting things
right. For everyone who complains that their software is broken, there will be
two assholes who claim that it&#8217;s not. The spec, whose primary purpose is
to arbitrate disputes between morons and assholes, will fail to resolve
anything, and the arguments will smolder for years.</span></p>

<p class=MsoNormal><span style='font-size:10.0pt;font-family:Verdana'>&nbsp;</span></p>

<p class=MsoNormal><span style='font-size:10.0pt;font-family:Verdana'>If your
spec is good enough, morons have a fighting chance of getting things right the
second time around, without being besieged by assholes. Meanwhile, the assholes
who have nothing better to do than look for loopholes won&#8217;t find any, and
they&#8217;ll eventually get bored and wander off in search of someone else to
harass.</span></p>

</div>

