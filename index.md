<p align="center">
  <img src="images/logo-mat.png" alt="MAT's logo"/>
</p>


# Welcome session 

Wednesday 14 October at 16:00 in this link: [meet.google.com/yee-hwvw-dgw](meet.google.com/yee-hwvw-dgw)


# Online sessions scheduled

{% assign sorted = site.posts | sort: 'date' %}
<ul>
  {% for post in sorted %}
    <li>
      <a href="{{site.baseurl}}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


# Overview

Welcome to the supporting website for the "Elements of Mathematics" a.k.a. "mat" course. This course is run in remote-online, 
partially-asynch mode, which means that the interaction between the teachers and the students will be telematic, and part 
of the content supplied to the students will not be delivered during the scheduled sessions. For the most part, the 
students should watch/read and process lecture content before meeting online.


# Online sessions

Each session will cover a series of related topics. Here is the [calendar]({{ site.baseurl }}{% link docs/calendar.pdf %})
of the sessions. The content for each session is available in each session's page (links in the top), including 
the syllabus, required content, link to the telematic room and collection of exercises for practice.

The sessions will serve several purposes:

1. Summarizing main take-homes from lecture content
2. Solve exercises
3. Q&A and discussion
4. Run tutorials


# Telematic room

We will be using the [google-meet](https://meet.google.com/) platform for meeting online. Every session will have a 
possibly different link that will be posted in the respective session page.


# Evaluation

Proof of work will come in three flavours:

1. Specific assignments proposed along the course.
2. In-depth processing of a [computational biology paper](https://random-computational-biology-papers.org).
3. Final test.

Tentative weighting for the score: 20% (1) + 30% (2) + 50% (3).

# Teachers

Ferran Muiños is the course coordinator. You can learn a bit more about his background and credentials 
[here](https://www.upf.edu/web/bioinformatics/entry/-/-/ferran_muinos-irbbarcelona_org/adscripcion/ferran-mui%C3%B1os).

Ramon Massoni will act as invited speaker and teaching assistant for the three linear algebra tutorials. 
You can find more about his work on his [github repo](https://github.com/massonix) and on [twitter](https://twitter.com/rmassonix).

We were both students of this master back in the old good days.
