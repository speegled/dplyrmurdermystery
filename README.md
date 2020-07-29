# tidyverse-murder-mystery
SQL murder mystery modified for the `tidyverse`

There's been a murder in the tidyverse! A crime has taken place and the detective needs your help. The detective gave you the crime scene report, but you somehow lost it. You vaguely remember that the crime was a **murder** that occurred sometime on **Jan.15, 2018** and that it took place in **dplyr City**. 

Use the data sets included in `data` to figure out whodunnit! You can load the data frames into R by typing `load("data/dplyr_murder_mystery.Rda")`

This project started as a clone of https://mystery.knightlab.com/, with **SQL City** changed to **dplyr City**, which itself was inspired by a murder in Terminal City https://github.com/veltman/clmystery. 

# Goals

I would like to make this a community project to make this murder mystery use more tidyverse tools. Currently, it can be solved using mostly `filter`, `str_detect` and `group_by`. It would be cool if more things were required. I am accepting pull requests that do the following:

1. Changes that do not affect the murder mystery itself. This includes adding funny testimonials, changing names to make them tidyverse specific, adding Easter Eggs that people don't expect, anything that makes it more fun to do the murder mystery, but doesn't change the plot of the mystery itself. You do not need to open an issue to create a pull request of this type. Simply make the change that you want, and submit the pull request. **Please also include the R code you used to make the change** when you submit the pull request.
2. Changes that **do** affect the murder mystery itself. These are a lot trickier. Please start by opening an issue that you would like to see addressed. For example, Issue: there is no visualization required to solve the mystery. Then, inside the issue you can explain how you would like to rectify the issue. Since there may be multiple people making suggestions, we will have to be careful not to introduce conflicts in the mystery itself. **Please also include the R code you used to make the change** when submitting the final pull request.
3. It would be nice to have a data dictionary, which tells people what variables are in which data frames, along with a brief description of the variable. I would love it if someone did that! 
4. Anything else that you think would make this more fun or educational! Please open an issue first before making changes like this. I am open to anything!

**PLEASE** be sure that you have completely solved the murder mystery before making any pull requests of type 2 and possibly 4! I am not going to post the solution, because I don't want to spoil it for people, but if you aren't sure whether you have completely solved it, please contact me before creating an issue. This is not strictly necessary for pull requests of type 1 above, but please indicate to me whether you have solved it or not, so that I know how carefully I need to check the change that you made!

# Code of Conduct

I expect all contributors to treat other contributors respectfully. Please report to me any behavior that is disrepectful in any way. Every contribtion is valued! I think this could be a great exercise for people learning the tidyverse, and it'll be fun to build it together! 

