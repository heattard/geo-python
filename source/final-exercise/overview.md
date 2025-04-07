# Final exercise assignment


> The final exercise is due by **2 May 2025**.

> To start the assignment: Create a `final-project` directory in your `exercises` directory


## The assignment
For this _Final Project_ you will be creating a 2 panel plot for your assigned SSW. I will _not_ be providing a jupyter notebook for this assignment. To create your own notebook, navigate to your `final-project` directory on the left-hand side of Jupyter and on the "Launcher page" click on the "Python 3" tile under "Notebook" As shown in the screenshot below

![click this link](img/screenshot-notebook-tile.png)


### Panel 1

The first panel will have the **climatological mean** 10 hPa nad 60N zonal-mean zonal wind for November - March **and** the 10 hPa 60 N zonal-mean zonal wind for the same period for _your SSW_. 

### Panel 2
The second panel, which can either be next to the first panel, or below it, will show the same variables but for the _4 week period_ that is +/- 2 weeks of the SSW onset date. 

### Requirements

#### Panel 1
1. Title that has the years included in the figure (i.e., 2007-2008)
2. labeled x and y axes
3. a box around the +/- 2 week period of the SSW
4. A thin line on the date of the SSW

#### Panel 2
1. Title that has the start and end date of the period
2. labeled x and y axes
3. A line on the start date of the SSW

#### A few notes

>Note that the two panels **do not** need to have the same y axes.

>If you think that your Panel 2 (the zoom in version) should be over a different time period (e.g., +/- 3 weeks) because it shows the evoluation of the wind better, go ahead!

>Make sure to save your figure as as PNG

>Make sure to commit and push your edits to github!!!

#### The data
- The climotologlical mean data is in `/data/merra2/climo/u10hPa60N_climo.csv`
- The daily data for all years is in `/data/merra2/u_10hPa_60N.csv`

#### The Presentaion
On 2 May 2025 you will give a 5-minute presentation about your plots, which must include:
1. A brief overview of the SSW:
    - the date of the SSW
    -  a **short** discussion of how _anomalous_ this was for the season (e.g., was the wind stronger than usual at the beginning of the season and then rapidly decrease?
2. A discussion of the plots.  Consider the questions below and address 2-3 of them: 
   - did you keep the +/- 2 week period? why/why not?
   - How did you make the box? the line?
   - Did you do anything different/special?
   - Was something particularly difficult? How did you figure out how to do it?
   - was there something you _wanted_ to do but couldn't figure out how to do?
   - anything else that addresses the plots 
