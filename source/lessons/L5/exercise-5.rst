Exercise 5
==========

.. note::

    Please complete this exercise by **1 April 2025**.

.. admonition:: Start your assignment

    **You can start working on your copy of Exercise 5 by** making a copy of the exercise 4 directory that is in /shared to your own home directory  

    To do this, follow the instructions from `lesson 2 <https://geo-python-heattard.readthedocs.io/en/latest/lessons/L2/exercise-2.html#exercise-2>`__ but change **exercise-2** to **exercise-5**

You can also take a look at the template repository for `Exercise 5 on GitHub <https://github.com/Geo-Python-2023/Exercise-5>`__ (does not require logging in).

Note that you should not try to make changes to this copy of the exercise, but rather only to the copy available via GitHub Classroom.


Exercise 5 hints
----------------

Below are some tips for working on Exercise 5.

Selecting date ranges
~~~~~~~~~~~~~~~~~~~~~

In the Part 3 of Problem 3, the aim is to select rows that belong to certain month. The key here is to understand that
the data values in the ``YR--MODAHRMN`` column are integer numbers using a format ``YYYYMMDDHHmm`` where ``YYYY`` is the
year of the observation, ``MM`` is the month, ``DD`` is the day, ``HH`` is the hour, and ``mm`` is the minute.

Using these values it is possible to make simple mathematical queries such as finding the values starting from the beginning of August, 2017:

.. code-block:: python

    august_values = data.loc[data['YR--MODAHRMN'] >= 201708010000]

Here, the value ``201708010000`` corresponds to the first day of August at the hour 00:00.