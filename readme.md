# Python for data science, machine learning, and scientific computing

Python is one of the most widely used and highly valued programming languages
in the world, and is especially widely used in data science, machine learning,
and in other scientific computing applications. This course provides both a
general introduction to programming with Python and a comprehensive
introduction to using Python for data science, machine learning, and scientific
computing. The major topics that we will cover include the following: the
fundamentals of general purpose programming in Python; using `Jupyter`
notebooks as a reproducible interactive Python programming environment;
numerical computing using `numpy`; data processing and manipulations using
`pandas`; data visualization using `matplotlib`, `seaborn`, `ggplot`, `bokeh`,
`altair`, etc; symbolic mathematics using `sympy`; data science and machine
learning using `scikit-learn`, `PyTorch`; high performance computing with `Numba`,
`IPyParallel`, `Dask`.  Overall, this course aims to provide a solid
introduction to Python generally as a programming language, and to its
principal tools for doing data science, machine learning, and scientific
computing. (Note that this course will focus on Python 3 exclusively given that
Python 2 has now reached it end of life).

## Intended Audience

This course is aimed at anyone who is interested in learning the fundamentals
of Python generally and especially how Python can be used for data science,
broadly defined.  Python and Python based data science is applicable to
academic research in all fields of science and engineering as well as data
intensive industries and services such as finance, pharmaceuticals, healthcare,
IT, and manufacturing.

## Teaching Format

This course will be hands-on and workshop based. Throughout each day, there
will be some lecture style presentation, i.e., using slides, introducing and
explaining key concepts. However, even in these cases, the topics being covered
will include practical worked examples that will work through together.

The course will take place online using Zoom. On each day, the live video broadcasts will occur between (British Summer Time, UTC+1, timezone) at:

* 10am-12pm
* 1pm-3pm
* 4pm-6pm
 
However, all sessions will be video recorded and made available to all attendees as soon as possible, hopefully soon after each 2hr session.
  
Attendees in different time zones will be able to join in to some of these live broadcasts, even if all of them are not convenient times.
For example, attendees from North America may be able to join the live sessions at 1pm-3pm and 4pm-6pm, and then catch up with the 10am-12pm recorded session when it is uploaded (which will be soon after 6pm each day). 
By joining any live sessions that are possible, this will allow attendees to benefit from asking questions and having discussions, rather than just watching prerecorded sessions. 
In addition, the fifth and final day of the course is an open session that allows for any spill-over of content, any revision or repetition of topics, and will provide an opportunity for any remaining questions or discussions.



## Assumed quantitative knowledge

We will assume only a minimal amount of familiarity with some general
statistical and mathematical concepts. These concepts will arise when we
discuss numerical computing, symbolic maths, and statistics and machine
learning. However, expertise and proficiency with these concepts are not
necessary. Anyone who has taken any undergraduate (Bachelor's) level course on
(applied) statistics or mathematics can be assumed to have sufficient
familiarity with these concepts.

## Assumed computer background

No prior experience with Python or any other programming language is required.
Of course, any familiarity with any other programming will be helpful, but is not
required.  

## Equipment and software requirements

Attendees of the course should bring a laptop computer with Python (version 3)
and the Python packages that we will use (such as `numpy`, `pandas`, `sympy`, etc)
installed. All the required software is free and open source and is available
on Windows, MacOs, and Linux. Instructions on how to install and configure all
the software are [here](installation_instructions.md). We will
also provide time during the workshops to ensure that all software is installed
and configured properly.

# Course programme 

## Monday 

* Topic 1: *The What and Why of Python*. In order to provide some general
  background and context, we will describe Python where came from, what its
  major design principles and intended use was originally, and where and how it
  is now currently used. We will see that Python is now extremely widely used,
  especially in powering the web, in data science and machine learning, and
  system level programming. Here, we also compare and contrast Python and R,
  given that both are extremely widely used in data science.

* Topic 2: *Installing and setting up Python*. There are many ways to write and
  execute code in Python. Which to use depends on personal preference and the
  type of programming that is being done.  Here, we will explore some of the
  commonly used Integrated Development Environments (IDE) for Python, which
  include *Spyder* and *PyCharm*. Here, we will also mention and briefly describe
  `Jupyter` notebooks, which are widely used for scientific applications of
  Python, and are an excellent tool for doing reproducible interactive work. We
  will cover `Jupyter` more extensively starting on Day 3.  Also as part of this
  topic, we will describe how to use *virtual environments* and package
  installers such as *pip* and *conda*.

* Topic 3: *Introduction to Python: Data Structures*. We will begin our
  coverage of programming with Python by introducing its different data
  structures.and operations on data structures This will begin with the
  elementary data types such as integers, floats, Booleans, and strings,
  and the common operations that can be applied to these data types.
  We will then proceed to the so-called *collection* data structures, 
  which primarily include lists, dictionaries, tuples, and sets.

* Topic 4: *Introduction to Python: Programming*. Having introduced Python's
  data types, we will now turn to how to program in Python. We will begin
  with iteration, such as the `for` and `while` loops. We will then cover
  conditionals and functions.


## Tuesday

* Topic 5: *Modules, packages, and imports*. Python is extended by 
  hundreds of thousands of additional packages. Here, we will cover how
  to install and import these packages, and also how to write our own modules
  and packages.

* Topic 6: *Numerical programming with `numpy`*. Although not part of Python's
  official standard library, the `numpy` package is the part of the de facto
  standard library for any scientific and numerical programming. Here we will
  introduce `numpy`, especially `numpy` arrays and their built in functions (i.e.
  "methods"). Here, we will also consider how to speed up `numpy` code using the
  `Numba` just-in-time compiler. In addition, we will consider how to do parallel
  programming using `IPyParallel` and `Dask`.

* Topic 7: *Data processing with `pandas`*. The `pandas` library provides means to
  represent and manipulate data frames. Like `numpy`, `pandas` can be see as part
  of the de facto standard library for data oriented uses of Python.

* Topic 8: *Object Oriented Programming*. Python is an object oriented language
  and object oriented programming in Python is extensively used in anything
  beyond the very simplest types of programs. Moreover, compared to other
  languages, object oriented programming in Python is relatively easy to learn.
  Here, we provide a comprehensive introduction to object oriented programming
  in Python.

* Topic 9: *Other Python programming features*. In this section, we will cover
  some important features of Python not yet covered. These include exception handling,
  list and dictionary comprehensions, `itertools`, advanced collection types including
  `defaultdict`, anonymous functions, decorators, etc.

## Wednesday

* Topic 10: *`Jupyter` notebooks and `Jupyterlab`*. Although we have already
  introduced `Jupyter` notebooks, here we will explore them properly. `Jupyter`
  notebooks are reproducible and interactive computing environment that support
  numerous programming languages, although Python remains the principal language
  used in `Jupyter` notebooks. Here, we'll explore their major features and 
  how they can be shared easily using GitHub and Binder.

* Topic 11: *Data Visualization*. Python provides many options for data
  visualization.  The `matplotlib` library is a low level plotting library that
  allows for considerable control of the plot, albeit at the price of a
  considerable amount of low level code. Based on `matplotlib`, and providing a
  much higher level interface to the plot, is the `seaborn` library. This allows
  us to produce complex data visualizations with a minimal amount of code.
  Similar to `seaborn` is `ggplot`, which is a direct port of the widely used R
  based visualization library. In this section, we will also consider a set of
  other visualization libraries for Python. These include `plotly`, `bokeh`, and
  `altair`.

* Topic 12: *Symbolic mathematics*. Symbolic mathematics systems, also known as
  computer algebra systems, allow us to algebraically manipulate and solve
  symbolic mathematical expression. In Python, the principal symbolic
  mathematics library is `sympy`. This allows us simplify mathematical
  expressions, compute derivatives, integrals, and limits, solve equations,
  algebraically manipulate matrices, and more. 

* Topic 13: *Statistical data analysis*. In this section, we will describe
  how to perform widely used statistical analysis in Python. Here we will 
  start with the `statsmodels`, which provides linear and generalized
  linear models as well as many other widely used statistical modelsi. We 
  will also cover `rpy2`, which is and interface from Python to R. This
  allows us to access all of the the power of R from within Python.

## Thursday

* Topic 14: *Machine learning*. Python is arguably the most widely used language
  for machine learning. In this section, we will explore some of the major 
  Python machine learning tools that are part of the `scikit-learn` package. 
  Here, we will cover machine learning tools such as support vector machines, decision trees,
  random forests, k-means clustering, dimensionality reduction, model evaluation,
  and cross-validation.

* Topic 15: *Neural networks and deep learning*. A popular subfield of machine 
  learning involves the use of artificial neural networks and deep learning methods.
  In this section, we will explore neural networks and deep learning using the `pytorch` library. Examples 
  that we will consider here include image classification and other classification 
  problems taken from, for example, the UCI Machine Learning Repository.

## Friday

* Wrap up and open session: The final day will be an open session. We will
  cover any topic that attendees would like to cover. This could include going
  deeper into some topic already covered, or else introducing new Python topics
  that we did not cover. We can also deal with specific Python related problems
  that attendees have, and these can be in one-to-one meetings or with the
  entire group.
