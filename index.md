---
layout: default
title: Home
seo:
  type: Course
  name: {{ site.title }}
nav_order: 1
---

# {{ site.tagline }}

<!--{% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}-->

This course provides a broad and deep treatment of statistical and machine learning approaches to time series.  Students entering the course are assumed to have foundational working knowledge in statistics and probability, though the course has been designed to provide a broadly accessible treatment of the topics covered.  

The first half of the course covers traditional statistical time series concepts and approaches whereas the second half delves into more modern statistical and machine learning methods for time series.  Topics covered include:
* Stationarity, autocorrelation, and basic theoretical constructs
* Data wrangling – detrending, smoothing, and data transformations
* AR, MA, ARMA, and ARIMA/SARIMA models
* Forecasting
* Estimation of ARMA models
* State space models, filtering/smoothing, estimation
* Deep learning for time series – RNNs, CNNs, etc.
* Granger causality
* Gaussian processes
* Discrete-valued time series
* Switching linear dynamical systems

## Teaching team

{% assign instructors = site.staffers | sort: 'index' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## Course Logistics
&nbsp;

**When**: Class is Mondays and Wednesdays 1:30-2:50pm PST.

**Where**: Class will be in person at McCullough Building, Rm 115.

**Links**:
- [Ed]():
  This is the main way that you and the teaching team should communicate:
  we will post all important announcements here, and you should ask
  all course-related questions here.
  For personal matters that you don't wish to put in a private Ed post, you can
  email the teaching staff at [stats207-aut2223-staff@lists.stanford.edu](mailto:stats207-aut2223-staff@lists.stanford.edu).
- [Canvas](): The course Canvas page
  contains links and resources only accessible to students.
- [Gradescope](): We use Gradescope for managing coursework (turning in, returning grades).  Please use your
  @stanford.edu email address to sign up for a Gradescope account.

**Prerequisites**: A well-prepared student will have knowledge of:
  * Math:
    * Linear algebra (matrix/vector operations, orthogonality, etc.)
    * Multivariate calculus (gradients, partial derivatives)
  * Probability:
    * Random variables, expectations, Gaussian distribution, conditional and marginal distributions
  * Statistics / machine learning basics:
    * Linear regression and classification and, ideally, overfitting and bias-variance tradeoff
    * Parameter estimation, including via maximum likelihood estimation
    * Confidence intervals
  * Programming proficiency in:
    * Python (preferred for this course) or R
    * or Julia, etc. with an ability to (i) pivot to Python with starter code or (ii) code independently in selected language

From experience, eager students with a strong quantitative background are able to catch up and fully participate.  

**Course Grade**: The course grade will be based on the following components.

- 5 Homework Assignments (45%): HW0 (5%), HW1 - HW4 (40%)
- Concept Quizzes (15%)
- Final Project (40%)

**Textbooks**:
  1. "Time Series Analysis and Its Application" by Schumway & Stoffer
  2. "[New Introduction to Multiple Time Series Analysis](https://link.springer.com/book/10.1007/978-3-540-27752-1)" by Helmut Lütkepohl