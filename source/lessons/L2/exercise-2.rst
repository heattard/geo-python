Exercise 2
==========

.. note::

    This assignment is a work in progress as of 2/6/25

.. admonition:: Original Exercise
    You can also take a look at the template repository for `Exercise 2 on GitHub <https://github.com/Geo-Python-2023/Exercise-2>`__ (does not require logging in) from the original creators of this course. Note that you should not try to make changes to this copy of the exercise and that it may be slightly different than the version we are using

Getting Started 
----------------
    **You can start working on your copy of Exercise 2** by copying the prepared Jupyter notebook and README file from the shared exercise directory. 

Follow the directions below 
    In your terminal:
    1. Navigate to your exercise directory
    2. Run the following code 

.. code:: console

    cp -r /shared/geo-python2025/exercises/exercise-2/ .

This will copy the exercise-2 directory and its contents into your own directory.  To see what's inside the new directory run the following: 

.. code:: console

    cd exercise-2

.. code:: console

    ls

You should see "Exercise-2.ipynb" and "README.md"

Open the README.md file in JupyterLab and you will see the directions.  

**You will be editing the 'Exercise-2.ipynb' file for this assignment.** 


Exercise 2 hints
----------------

Here are a few things that may be helpful in completing Exercise 2.

Git
~~~

You can find step-by-step instructions for using Git on the course page titled :doc:`git-basics`.
Remember to commit your changes after each major edit! Also, it's better to push your changes to GitHub frequently, rather than only at the very end of the exercise.

Indentation woes
~~~~~~~~~~~~~~~~

We have not really run into this problem in the lessons, but Python codes are sensitive to how much you indent the start of each line.
This is perhaps easiest to see with an example.

.. code:: python

    name = 'Dave'
        dogs = 0
    print('My name is', name, 'and I own', dogs, 'dogs.')

If you copy and paste this code into a **Jupyter Notebook** cell and run it, you will see that is gives an ``IndentationError``.

.. code:: python

        dogs = 0
        ^
    IndentationError: unexpected indent

We will see examples later of why indentation matters, but for now just be sure you don't indent lines to different levels.
Thus, the fix is simply to remove the spaces on the second line.

.. code:: python

    name = 'Dave'
    dogs = 0
    print('My name is', name, 'and I own', dogs, 'dogs.')

Now, running the code results in the expected output.

.. code:: python

    My name is Dave and I own 0 dogs.
