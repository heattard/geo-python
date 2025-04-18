.. Geo-Python documentation master file, created by
   sphinx-quickstart on Thu Aug 23 14:00:02 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. image:: img/banner/geo-python-2023.png
    :class: dark-light

Welcome to Geo-Python 2025!
===========================

The **Geo-Python** course teaches you the basic concepts of programming and scientific data analysis using the Python programming language in a format that is easy to learn and understand (no previous programming experience required).
Each lesson is a tutorial with specific topic(s) where the aim is to gain skills and understanding how to solve common data-related tasks using Python.
Geo-Python is jointly organized by the `Master's Program in Geography <https://www.helsinki.fi/en/degree-programmes/geography-masters-programme>`_ and the `Bachelor's Program in Geoscience <https://www.helsinki.fi/fi/koulutusohjelmat/geotieteiden-kandiohjelma>`_ at the University of Helsinki.

.. admonition:: Daemen University students

    This course will be used as *part* of the course NSC 457. 

Course format
-------------

The majority of this course will be spent in front of a computer learning to program in the Python language.
The course consists of interactive lectures and weekly exercises.
The exercises will focus on developing basic programming skills using Python and applying those skills to various analytical problems.
Typical exercises will involve a brief introduction followed by topical computer-based tasks.
For each exercise, you may be asked to submit the Python codes you have written, output figures and answers to related questions.
You are encouraged to discuss and work together with other students while working on the weekly exercises.
However, the exercises you submit must must clearly reflect your own work (in short, don't copy/paste from other students).

Course topics
-------------

After completing this course, students will (1) understand basic programming concepts, (2) be able to write short programs, and (3) manipulate, analyze, and visualize scientific data using Python.
Students will also learn to use version control (git) and online repositories (GitHub) for documenting and sharing their work.
Themes for each week are listed below.
You can also read more about the weekly :doc:`learning goals <course-info/learning-goals>`.

The course has 7 themes that will be addressed throughout the semester.   

+----------+----------------------+
| Number   | Theme                |
+==========+======================+
|**1**     | Basic concepts of    |
|          | Python and computer  |
|          | programs             |
|          |                      |
+----------+----------------------+
|**2**     | Diving into Python   |
|          |                      |
|          |                      |
+----------+----------------------+
|**3**     | Repeating tasks      |
|          | and making decisions |
|          |                      |
|          |                      |
+----------+----------------------+
|**4**     | Creating and using   |
|          | functions            |
|          |                      |
+----------+----------------------+
|**5**     | Data analysis        |
|          | Part I               |
|          |                      |
+----------+----------------------+
|**6**     | Data analysis        |
|          | Part II +            |
|          | Dealing with errors  |
+----------+----------------------+
|**7**     | Data visualization   |
|          |                      |
|          |                      |
+----------+----------------------+


.. admonition:: Step by step instructions with cloud computing!

    The materials are presented in a way that you can follow them step by step exactly as they are written, as long as you use the computing resources that we provide for you (namely JupyterLab Notebooks using Binder or CSC Cloud computing resources).
    If you would like, you can find :doc:`more information about our cloud computing environment <lessons/L1/course-environment-components>`.
    For those planning to work on the course materials on your own computer, please note that you will **need to adjust the file paths to the data** accordingly.

.. admonition:: For teachers

    If you would like to use these materials for your own teaching or develop them further, we highly support that.
    Please read more about how to do it from :doc:`our licensing terms<course-info/licensing>`.

.. toctree::
    :maxdepth: 2
    :caption: Course information

    course-info/course-info
    course-info/learning-goals
    course-info/grading
    course-info/ai-tools
    course-info/licensing
    ..
        course-info/theteam

.. toctree::
    :maxdepth: 2
    :caption: Lesson 1

    lessons/L1/motivation
    lessons/L1/overview
    lessons/L1/course-environment-components
    lessons/L1/discord-usage
    notebooks/L1/a-taste-of-python.ipynb
    notebooks/L1/gcp-1-variable-naming.ipynb
    exercises/set-up-github.md
    exercises/exercise-1.md

.. toctree::
    :maxdepth: 2
    :caption: Lesson 2

    lessons/L2/overview
    notebooks/L2/Python-basic-elements.ipynb
    lessons/L2/intro-to-GitHub
    lessons/L2/git-basics
    notebooks/L2/gcp-2-describing-code.ipynb
    lessons/L2/exercise-2

.. toctree::
    :maxdepth: 2
    :caption: Lesson 3

    lessons/L3/overview
    notebooks/L3/for-loops.ipynb
    notebooks/L3/conditional-statements.ipynb
    notebooks/L3/gcp-3-pep8.ipynb
    lessons/L3/exercise-3

.. toctree::
    :maxdepth: 2
    :caption: Lesson 4

    lessons/L4/overview
    notebooks/L4/functions.ipynb
    notebooks/L4/script-files.ipynb
    notebooks/L4/modules.ipynb
    notebooks/L4/gcp-4-writing-scripts.ipynb
    lessons/L4/exercise-4

.. toctree::
    :maxdepth: 2
    :caption: Lesson 5

    lessons/L5/overview
    lessons/L5/pandas-overview.rst
    notebooks/L5/exploring-data-using-pandas.ipynb
    notebooks/L5/processing-data-with-pandas.ipynb
    lessons/L5/exercise-5

.. toctree::
    :maxdepth: 2
    :caption: Lesson 6

    lessons/L6/overview
    notebooks/L6/advanced-data-processing-with-pandas.ipynb
    notebooks/L6/errors.ipynb
    notebooks/L6/debugging.ipynb
    lessons/L6/exercise-6

.. toctree::
    :maxdepth: 2
    :caption: Lesson 7

    lessons/L7/overview
    lessons/L7/python-plotting
    lessons/L7/plot-anatomy
    notebooks/L7/basic-plotting.ipynb
    notebooks/L7/line-plots.ipynb
    notebooks/L7/subplots.ipynb
    lessons/L7/s

.. toctree::
    :maxdepth: 2
    :caption: Final exercise

    final-exercise/overview

.. toctree::
    :maxdepth: 2
    :caption: Resources

    course-info/python-vocabulary
    course-info/installing-miniconda
    course-info/resources
