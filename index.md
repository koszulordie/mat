<p align="center">
  <img src="images/logo-mat.png" alt="MAT's logo"/>
</p>


# Next session 

Let's meet in the Collaborate session posted in the Aula Global MAT course page.


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

After some nasty practical issues, we will be using the [collaborate](https://www.blackboard.com/teaching-learning/collaboration-web-conferencing/blackboard-collaborate) 
web conferencing platform instead of **google-meet**. Every session will have a possibly different link that will be posted in the Aula Global.


# Evaluation

Proof of work will come in three flavours:

1. Specific assignment proposed during the course.
2. [Computational biology paper through the lens of math]({{ site.baseurl }}{% link papers/papers.md %}).
3. <s>Final test</s>

Tentative weighting for the score: 30% (1) + 70% (2).


# Teachers

Ferran Muiños is the course coordinator. You can learn a bit more about his background and credentials 
[here](https://www.upf.edu/web/bioinformatics/entry/-/-/ferran_muinos-irbbarcelona_org/adscripcion/ferran-mui%C3%B1os).

Ramon Massoni will act as invited speaker and teaching assistant for the three linear algebra tutorials. 
You can find more about his work on his [github repo](https://github.com/massonix) and on [twitter](https://twitter.com/rmassonix).

We were both students of this master back in the old good days.

# References

## Specific for this course

**Introduction to Linear Algebra.**

Gilbert Strang. URL: [http://math.mit.edu/~gs/linearalgebra](http://math.mit.edu/~gs/linearalgebra)

**3Blue1Brown YouTube Channel.**

Grant Sanderson. URL: [https://www.youtube.com/c/3blue1brown](https://www.youtube.com/c/3blue1brown)

**Elementary Classical Analysis.** 

Jerrold E. Marsden, Michael J. Hoffman. W. H. Freeman, 1993.

**Infinite Powers: How Calculus Reveals the Secrets of the Universe.**

Steven Strogatz. Houghton Mifflin Harcourt, 2019.

## Off-topic

**Concrete Mathematics: A Foundation for Computer Science.**

Ronald L. Graham, Donald E. Knuth, Oren Patashnik. Addison-Wesley, 1994.

**The Art of Computer Programming (Volume 1): Fundamental Algorithms.**

Donald E. Knuth. Addison-Wesley, 1968.
