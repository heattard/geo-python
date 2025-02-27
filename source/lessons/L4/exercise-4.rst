Exercise 4
==========

.. note::

    Please complete this exercise by **21 March 2025**.

.. admonition:: Start your assignment

    **You can start working on your copy of Exercise 4 by** making a copy of the exercise 4 directory that is in /shared to your own home directory  

    To do this, follow the instructions from `lesson 2 <https://geo-python-heattard.readthedocs.io/en/latest/lessons/L2/exercise-2.html#exercise-2>`__ but change **exercise-2** to **exercise-4**

You can also take a look at the template repository for `Exercise 4 on GitHub <https://github.com/Geo-Python-2023/Exercise-4>`__ (does not require logging in).


Exercise 4 hints
----------------

Here are a few things that may be helpful in completing Exercise 4.

Importing variables from a script
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

In the lesson materials we saw how to `import functions from a script <../../notebooks/L4/functions.html#calling-functions-from-a-script-file>`__.

In a similar manner you can also import any variable that has been defined in another script, hence, it is not limited
to functions that you can import.

Counting values from a list
~~~~~~~~~~~~~~~~~~~~~~~~~~~

In some cases it might be useful to know how many times certain value exists in a list. Consider following example:

.. code-block:: python

    my_list = ['car', 'bus', 'bike', 'car', 'car', 'bike']
    car_count = my_list.count('car')
    print("There are", car_count, "cars in my list!")