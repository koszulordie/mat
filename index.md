<p align="center">
  <img src="images/logo-mat.png" alt="MAT's logo"/>
</p>

# Elements of Mathematics (MAT)

Welcome to the supporting website for the **Elements of Mathematics** course of the [Master in
 Bioinformatics for Health Sciences](https://www.upf.edu/web/bioinformatics). 
 
# Fall 2021-2022

{% assign sorted = site.posts | sort: 'date' %}
<ul>
  {% for post in sorted %}
    <li>
      <a href="{{site.baseurl}}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

# Timetable

Check the [official timetable](https://gestioacademica.upf.edu/pds/consultaPublica/look%5Bconpub%5DInicioPubHora
?entradaPublica=true&idiomaPais=ca.ES&centro=804&estudio=8045&PlanDocente=2021) for the fall 2021 term.

# Content

Each session has its own page including the syllabus, content to be watched/read before the session (entirely optional but recommended), links to exercises for practice and supplementary content.

Sessions will be ~2h covering a bunch of related topics. To make the most our of each session it would be beneficial to watch/read content supplied before the session takes place.

## Aim

The sessions will serve several purposes:

1. Present fundamental concepts
2. Solve exercises
3. Q&A and discussion
4. Run tutorials

## Remote sessions

Sessions on **13 and 20 october will be remote**. For remote sessions we will be using the [collaborate](https://www
.blackboard.com/teaching-learning/collaboration-web-conferencing/blackboard-collaborate) web conferencing platform. The remote session links will be posted in the Aula Global MAT page.

# Evaluation

Evaluation will have three components:

1. [Paper digest]({{ site.baseurl }}{% link papers/papers.md %})
2. Final test

Weighting: 30% (1) + 70% (2)

# Teachers

**Ferran Muiños** will act as course coordinator. You can learn a bit more about his background by checking his publications in [biomedicine](https
://pubmed.ncbi.nlm.nih.gov/?term=Mui%C3%B1os+F%5BAuthor%5D&sort=date) and [math](https://zbmath.org/?q=ai%3Amuinos.ferran).

**Ramon Massoni** will act as invited speaker and teaching assistant for the tutorials. 
You can find more about his work on his [github repo](https://github.com/massonix) and on [twitter](https://twitter.com/rmassonix).

We were both students of this master back in the old days.

# References

## Specific for this course

**[Introduction to Linear Algebra](http://math.mit.edu/~gs/linearalgebra).**
Gilbert Strang.

**[3Blue1Brown YouTube Channel](https://www.youtube.com/c/3blue1brown).**
Grant Sanderson.

**[Steve Brunton's YouTube Channel](https://www.youtube.com/channel/UCm5mt-A4w61lknZ9lCsZtBw).**
Steve Brunton.

**[A friendly introduction to linear algebra for Machine Learning](https://www.youtube.com/watch?v=LlKAna21fLE).**
Tai Danae Bradley. TensorFlow ML Tech Talks.

**[The Art of Linear Algebra](https://github.com/kenjihiranabe/The-Art-of-Linear-Algebra).**
Kenji Hiranabe.

**Infinite Powers: How Calculus Reveals the Secrets of the Universe.**
Steven Strogatz. Houghton Mifflin Harcourt, 2019.

## Miscelanea

**[Yann LeCun’s Deep Learning Course at CDS](https://cds.nyu.edu/deep-learning/).**
Yann LeCun, Alfredo Canziani.

**[Introduction to Linear Algebra for Applied Machine Learning with Python](https://pabloinsente.github.io/intro-linear-algebra).**
Pablo Cáceres.
