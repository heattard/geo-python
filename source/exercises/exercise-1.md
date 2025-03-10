# Exercise 1: Cooking up some Python

In the “Taste of Python” lesson this week we have learned a few basic things in Python. Now you get your chance to demonstrate your skills.

This exercise is inspired by [Finland being ranked the world's happiest country for the 6th year in a row](https://yle.fi/a/74-20023112). As the instructors of the Geo-Python course, we think we've found a better way to assess the individual happiness of people in Finland (particularly those taking this course!), and we're going to test our idea with you. In *five easy steps (or problems)* we'll be able to reveal your happiness based on two of life's most important happiness factors: Ice cream and sleep!

> This page has been updated as of 1:40pm on 3 February 2025.  

## Problem 1 - Creating your own Jupyter notebook
   
1. `cd` into your `geo-python-exercises` directory
   
2. Open Jupyter lab from the browser as was discussed in class and create a new notebook in your `exercise-1` directory.

3. Use the file browser on the left side of the Jupyter Lab window to change the name of your notebook file to `exercise-1.ipynb`.

## Problem 2 - Add the notebook to your git repo

1. Go back to your terminal and make sure you are still in the `geo-python-exercises` directory
   
2. Type `git add exercise-1.ipynb` to add this file to your git repository

3. Type `git status` - this should say `No commits yet` and list the files that have changes to be commited. These files are said to be `staged` to commit meaning they have changes and are ready to be commited

4. Type `git commit -m "initial commit"`. This will commit all of your changes and include a message

<!---
2. Type `get init`. This makes this directory a git directory

3. Type `ls -al` you should see your `Exercise-1.ipynb` file listed *and* and directory called `.git`

4. Type `git add .` to add all the files from this directory to your git repository

5. Type `git status` - this should say `No commits yet` and list the files that have changes to be commited. These files are said to be `staged` to commit meaning they have changes and are ready to be commited

6. Type `git commit -m "initial commit"`. This will commit all of your changes and include a message

7. At this point if you run `git status` it should say there is nothing to commit, which means that all of your changes and version control are *stored locally*
---> 
<!---
## Problem 2.5 - Connect what you are doing locally to your github repository online
Note: The steps in Problem 2, 2.5, and Continuing to commit your work are from [this youtube video.](https://www.youtube.com/watch?v=jXpT8eOzzCM) 
9. In your github repository where you accepted the assignment, copy the link to your repo

10. In your termainal type `git remote add orgin <link to your repo>` (remove the <>).  This links your *local* repo to your repo online

11. Type `git push -u origin main`. This *pushes* the changes you made locally to your repo online

12. Enter your *github* username

13. Enter your *github* password

14. On your browser if you refresh the page on your github repo you can see all of the files you committed.
-->
## Continue to commit your code as you work
As you continue in this exericise you will be making changes to your notebook `Exercise-1.ipynb`. These changes need to be committed, so they are saved in your version control.

To commit a change you will run the same steps repeatedly from the terminal: 
1. `git add <filename>`

2. `git commit -m "short blurb about what changed"`

<!---
Periodically (**and always before you leave the lab**), you will need to *push* these changes to your online repository. To do this:
1. `git push`

2. Enter your *github* username

3. Enter your *github* password 
-->
## Problem 3 - Defining some numerical variables

In the top cell of the new notebook:

1. Create a variable called `ice_cream_rating` and use it to store an integer value (whole number) between 0 and 10 that reflects your general opinion about how much you enjoy eating ice cream.

2. Create another variable called `sleeping_rating` and use it to store another integer between 0 and 10 that reflects your opinion about how much you enjoy sleeping.

3. Run the cell by pressing <kbd>Shift</kbd> + <kbd>Enter</kbd>.

## Problem 4 - Defining some character string variables

In the new cell that appears:

1. Store your first name as a character string in a variable called `first_name`.

2. Store your last name as a character string in a variable called `last_name`.

3. (*Optional*) Define a third variable called `my_name` that will combine your first and last names into a single character string with a space between the names.

4. Run the cell by pressing <kbd>Shift</kbd> + <kbd>Enter</kbd>.

## Problem 5 - A bit of math

In order to assess your overall happiness it is necessary to combine the ice cream and sleeping ratings. To do this:

1. Calculate the average of your `ice_cream_rating` and `sleeping_rating` variables and store the resulting value in a variable called `happiness_rating`.

2. Run the cell by pressing <kbd>Shift</kbd> + <kbd>Enter</kbd>.

## Problem 6 - Checking data types

The next step is to investigate the kinds of data we're working with. In another Python cell:

1. Use a built-in Python function to check the data types of the `ice_cream_rating`, `first_name`, and `happiness_rating` variables. In order to see the data types for more than one variable in a single Python cell, you will need to print out these values using another built-in Python function.

2. Run the cell by pressing <kbd>Shift</kbd> + <kbd>Enter</kbd>.

3. Did all of the data types make sense? Were there any data types that were different than you expected? In the new Python cell that appeared after running the code above, type in your responses to these questions.

4. For the cell containing your answers to the questions above, change the kind of cell from **Code** to **Markdown**.

5. Run the Markdown cell by pressing <kbd>Shift</kbd> + <kbd>Enter</kbd>.

## Problem 7 - Displaying text on the screen

Finally, you can use your Python skills to generate output on the screen similar to that below. Use one command to generate each line of output.

```
My name is Dave and I give eating ice cream a score of 9 out of 10!
I am Dave Whipp and my sleeping enjoyment rating is 8 / 10!
Based on the factors above, my happiness rating is 8.5 out of 10, or 85.0 %!
```

Note that your code should replace “Dave” with the contents of your `first_name` variable, “9” with your value stored in the variable `ice_cream_rating`, etc. For your equivalent text with the full name (e.g., "Dave Whipp"), you can either use the values from the variables `first_name` and `last_name`, or the value in variable `my_name`.
<!---
## Finishing the exercise

To complete this exercise, make sure you have pushed your final changes to your github repository. Go to your github repo and look at your notebook (you can click on it and it will open in a read-only format) to make sure it has all of your final changes
--->