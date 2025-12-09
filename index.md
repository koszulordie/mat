<p align="center">
  <img src="images/logo-mat.png" alt="MAT's logo"/>
</p>

# Elements of Mathematics (MAT)

Welcome to the supporting website for the **Elements of Mathematics** course of the [Master in
 Bioinformatics for Health Sciences](https://www.upf.edu/web/bioinformatics). 
 
# Fall 2024-2025

{% assign sorted = site.posts | sort: 'date' %}
<ul>
  {% for post in sorted %}
    <li>
      <a href="{{site.baseurl}}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

# Content

Each session has its own page including a detailed syllabus and additional content to watch/read.

Sessions will have a duration of ~2h with a break between 1st and 2nd hour. To make the most out of each session it would be beneficial that the students have a look at the web content of each session before the session takes place.

## Aim

The sessions will serve several purposes:

1. Present fundamental concepts: definitions, examples and main theoretical results
2. Solving exercises
3. Q&A
4. Do hands-on tutorials

# Evaluation

Evaluation will have two components:

<!-- 1. [Integrative work]({{ site.baseurl }}{% link papers/papers.md %}) -- at most 30% of the grade -->
1. Integrative work -- at most 30% of the grade
2. Final test -- at least 70% of the grade


# Solved tests and exercises
1. [Final test - Fall 2024]({{ site.baseurl }}{% link solved-exercises/final-test-answers-2024.pdf %})
2. [Final test - Fall 2023]({{ site.baseurl }}{% link solved-exercises/final-test-answers-2023.pdf %})
3. [Final test - Fall 2022]({{ site.baseurl }}{% link solved-exercises/final-test-answers-2022.pdf %})
4. [Final test - Fall 2021 - 1st round]({{ site.baseurl }}{% link solved-exercises/final-test-answers-2021-1.pdf %})
5. [Final test - Fall 2021 - 2nd round]({{ site.baseurl }}{% link solved-exercises/final-test-answers-2021-2.pdf %})
6. [Mid term deliverable - Fall 2019]({{ site.baseurl }}{% link solved-exercises/mid-term-deliverable-2019.pdf %})
7. [Matrix algebra meets differential calculus]({{ site.baseurl }}{% link solved-exercises/exercises-matrix-algebra-and-calculus-solved.pdf %})

# Teachers

**Ferran Muiños** course coordinator. You can check his publications in [mathematics](https://zbmath.org/?q=au%3AFerran+Mui%C3%B1os) and [biology](https://pubmed.ncbi.nlm.nih.gov/?term=Ferran+Muin%CC%83os%5BAuthor%5D&sort=date).

**Paula Gomis** will act as invited speaker and teaching assistant for the hands-on sessions.


# References

## Specific for this course

**[Introduction to Linear Algebra](http://math.mit.edu/~gs/linearalgebra).**
Gilbert Strang.

**[3Blue1Brown YouTube Channel](https://www.youtube.com/c/3blue1brown).**
Grant Sanderson.

**[Steve Brunton's YouTube Channel](https://www.youtube.com/channel/UCm5mt-A4w61lknZ9lCsZtBw).**
Steve Brunton.

**Infinite Powers: How Calculus Reveals the Secrets of the Universe.**
Steven Strogatz. Houghton Mifflin Harcourt, 2019.

## Somewhat related miscelanea

**[Yann LeCun’s Deep Learning Course at CDS](https://cds.nyu.edu/deep-learning/).**
Yann LeCun, Alfredo Canziani.

**[Introduction to Linear Algebra for Applied Machine Learning with Python](https://pabloinsente.github.io/intro-linear-algebra).**
Pablo Cáceres.

**[A friendly introduction to linear algebra for Machine Learning](https://www.youtube.com/watch?v=LlKAna21fLE).**
Tai Danae Bradley. TensorFlow ML Tech Talks.

**[The Art of Linear Algebra](https://github.com/kenjihiranabe/The-Art-of-Linear-Algebra).**
Kenji Hiranabe.