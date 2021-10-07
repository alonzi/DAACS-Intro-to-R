
# Part III: Variables and Data Structures
In this part we are going to dig into some code and investigate what is going on. Along the way we will learn about variables and data structures. We will focus on Lines 15-19 in our sample code. I will guide you through the exercises.

## Exercise 1 - Variables
1. In the File left click 'SCV_BasicInventory.csv' and select "view file"
2. Explore the output that appears in editor window

3. Examine Line 18, but do not run it. Let's break it down.
`StewartCastleVillage  <- read_csv("SCV_BasicInventory.csv")`
    * 3 parts
      * the variable `StewartCastleVillage`
      * this thing `<-`
      * a function call `read_csv("SCV_BasicInventory.csv")`

4. Let's start with the function, enter the function call into the console and run it.
5. Explore the output it produces.

### Variables and this thing `<-`
In these steps we will explore the value of functions.
1. Take a look at line 18 again `StewartCastleVillage  <- read_csv("SCV_BasicInventory.csv")`
2. Run line 18
3. Enter `StewartCastleVillage` into the console and hit enter.

By comparing the function call and the variable we created you can see that we get the same result in the console. But now we have a peristent object, our variable, `StewartCastleVillage` for later use. It is not fleeting like the result of the function, you can see it in the Environment tab.

### Heuristic: The `<-` operator 'catches' the output of functions and stores them in variables.

## Exercise 2 - Data Structures
Now that we have finished getting our data from the csv file into a variable in memory we can explore the structure of that variable.


1. Take a look at the Environment panel and expand the `StewartCastleVillage` entry. Explore
2. Click on  `StewartCastleVillage` to open it in the editor window
3. Compare the csv file and the variable in the editor (same data, easier to use)

In the next part of the exercise we will explore `StewartCastleVillage`. It is data that we have put into a structure called a data frame.

**Jargon Note:** Formally we have created a 'tibble' and it falls into a general cateogry of data structure called a data frame. To quote Hadley "Tibbles are data frames"


4. 
5. Investigate `StewartCastleVillage` with the GUI
6. Investigate `StewartCastleVillage` with code
   * use typeof(...)
   * use length(...)

4. If we haven't seen an error message yet we will talk about error messages

### Heuristic: A tibble is a csv file stored in memory (and it has superpowers).




## And now for an Interlude about Domain Knowledge

## [On to part IV](https://github.com/alonzi/DAACS-Intro-to-R/blob/main/part-IV.md)

### Bonus: Transpose
a,b,c --> axb (c)
