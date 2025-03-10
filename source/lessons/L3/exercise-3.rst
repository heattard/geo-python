Exercise 3
==========

.. note::

    Please complete this exercise by **7 March 2025**.

.. admonition:: Start your assignment

    **You can start working on your copy of Exercise 3 by** making a copy of the exercise 3 directory that is in /shared to your own home directory  

    To do this, follow the instructions from `lesson 2 <https://geo-python-heattard.readthedocs.io/en/latest/lessons/L2/exercise-2.html#exercise-2>`__ but change **exercise-2** to **exercise-3**

You can also take a look at the template repository for `Exercise 3 on GitHub <https://github.com/Geo-Python-2023/Exercise-3>`__ (does not require logging in).
Note that you should not try to make changes to this copy of the exercise

Exercise 3 hints
----------------

Here are a few things that may be helpful in completing Exercise 3.

Tests
~~~~~

The exercise notebook contains some tests help you see if your code is working correctly. Some code cells contain
a line that says: `raise NotImplementedError()`. Always remove this piece of code from your submission and replace
it with your own code. The error tells us if you have not started the exercise.

Combining strings
~~~~~~~~~~~~~~~~~

In case you have forgotten, string variables can be added together. For example,

.. code-block:: python

    a = "Taco "
    b = "time"
    c = a + b
    print(c)

Nested if statements
~~~~~~~~~~~~~~~~~~~~

In some cases it might be useful to have nested if statements, meaning that you have another layer of
conditions after the first condition resolves to True.

Take a look of following example:

.. code-block:: python

    season = "Winter"
    temperature = 10

    if season == "Winter":

        if temperature > 7:
            print("No need for winter jacket!")

        else:
            print("It might be cold! Wear a proper jacket!")

   elif season == "Summer":

        if temperature > 20:
            print("It's warm! Time to wear shorts!")

        else:
            print("Well this is Finland, better wear long trousers!")
   else:
        print("Check the weather forecast!")
