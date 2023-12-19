<p align="center">
  <img src="images/logo-mat.png" alt="MAT's logo"/>
</p>

# Elements of Mathematics (MAT)

Welcome to the supporting website for the **Elements of Mathematics** course of the [Master in
 Bioinformatics for Health Sciences](https://www.upf.edu/web/bioinformatics). 
 
# Fall 2023-2024

{% assign sorted = site.posts | sort: 'date' %}
<ul>
  {% for post in sorted %}
    <li>
      <a href="{{site.baseurl}}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

# Timetable

Check the [official timetable](https://gestioacademica.upf.edu/pds/consultaPublica/look[conpub]InicioPubHora?entradaPublica=true&lock=true&@f7e536bed26c009727edf24c0a583d66=@9bee282a7d8e0091&@dee7125d9d9a52ef82586f940dcf3109=@12271687f1f1213a) for the fall 2023 term.

# Content

Each session has its own page including the syllabus and additional content to be watched/read.

Sessions will be ~2h covering a bunch of related topics. To make the most out of each session it would be beneficial to have a look at the content supplied before the session takes place.

## Aim

The sessions will serve several purposes:

1. Present fundamental concepts
2. Live exercise solving
3. Q&A
4. Run tutorials

# Evaluation

Evaluation will have two components:

1. [Paper digest]({{ site.baseurl }}{% link papers/papers.md %})
2. Final test

Weighting: 30% (1) + 70% (2)

# Exercises with answers
1. [Final test - Fall 2023]({{ site.baseurl }}{% link solved-exercises/final-test-answers-2023.pdf %})
2. [Final test - Fall 2022]({{ site.baseurl }}{% link solved-exercises/final-test-answers-2022.pdf %})
3. [Final test - Fall 2021 - 1st round]({{ site.baseurl }}{% link solved-exercises/final-test-answers-2021-1.pdf %})
4. [Final test - Fall 2021 - 2nd round]({{ site.baseurl }}{% link solved-exercises/final-test-answers-2021-2.pdf %})
5. [Mid term deliverable - Fall 2019]({{ site.baseurl }}{% link solved-exercises/mid-term-deliverable-2019.pdf %})


# Teachers

**Ferran Muiños** will act as course coordinator. You can check his publications [here](https://scholar.google.es/citations?user=PujyjakAAAAJ&hl=en).

**Paula Gomis** will act as invited speaker and teaching assistant. 

Both are alumni of the master.

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
