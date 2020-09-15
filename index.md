<p align="center">
  <img src="images/logo-mat.png" alt="MAT's logo"/>
</p>

# Overview

This is the supporting website for the "Elements of Mathematics" course. 

This course is run in **remote-online**, **partially-asynch** mode.

Interaction between the teachers and students will be telematic. 

Students will be responsible to watch/read lecture content elsewhere before each scheduled session. 
Then we will meet online at scheduled times to fulfill a few different activities:

1. Wrap up main take-homes from lecture content
2. Q&A
3. Solve exercises
4. Run tutorials

# Scheduled sessions

Each session will cover one specific topic. Here is a [calendar of online sessions](https://some-random-link.org), 
each with its own description, duties required before the session and exercises for practice.

# Telematic room

[Link to the telematic facility](https://some-random-link.org)

# Evaluation

Proof of work will come in three flavours:

1. Exercise assignments proposed throughout the course.
2. In-depth reading of a computational biology paper.
3. Final multiple-choice test.

# Teachers

Ferran Muiños is the course coordinator.
Ramon Massoni will act as invited speaker and teaching assistant in the linear algebra tutorials.

# Sessions

{% assign sorted = site.posts | sort: 'date' %}
<ul>
  {% for post in sorted %}
    <li>
      <a href="{{site.baseurl}}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

