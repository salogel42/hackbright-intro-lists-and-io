# File I/O

As you go through these exercises, make sure to commit after each change, and push your changes once you've completed the entire exercise!

## Part 1

1. Inside the local clone of this repository on your computer, navigate to the `file-exercises` directory.
2. Create a file called `[yourname]_fav_foods.txt`
3. In the file, list your 3 favorite foods from most favorite to least favorite. List only one food per line. 
5. Save the file.
*Remember to commit your changes at this point!*
4. Repeat steps 2-4 with your pair’s favorite foods.
6. Create a python file inside `file-exercises` called `compare_favs.py`
7. Inside of `compare_favs.py` do the following:
  1. open the file of your favorite foods.
  2. read all of your favorite foods into a list called `[your_name]_favs` <br>  *Remember to commit your changes at this point!*
  3. close the file
  4. open the file of your pair’s favorite foods.
  5. read all of your pair’s favorite foods into a list called `[their_name]_favs` 
  6. close the file <br> *Note: is there a way to avoid having this similar code repeated?  Try to think of a way to have the file reading code only once in your program, but still read both files! And remember to commit your changes!*
  7. create a function called `compare_favs` that takes two arguments, the list of your favs and the list of your pair’s. 
    1. This function should print "Our favorite foods are the same!" if your top favorite food is the same as your pairs.
    2. Otherwise, the function should print "Our favorite foods are different"
  8. Call the compare_favs function with your favs and your pair’s favs <br>*Remember to commit your changes at this point!*
9. Run `compare_favs.py`! Make sure it works!  Make sure to try lots of different inputs including some where they are the same and some not!

Example:
```
rachels_favs = [“barbeque”, “watermelon”, “ice cream”]
pauls_favs = [“mint oreos”, “pizza”, “barbeque”]
compare_favs(rachels_favs, pauls_favs)
⇒	“Our favorite foods are different”
```

## Part 2
Create a function called `compare_favs2` that prints out "We both love [food]!" for each food that you and your pair both enjoy.

Example:
```
rachels_favs = [“barbeque”, “watermelon”, “ice cream”]
pauls_favs = [“mint oreos”, “pizza”, “barbeque”]
compare_favs2(rachels_favs, pauls_favs)
⇒	“We both love barbeque!”
```
*Remember to commit and push your changes at this point!*

# Review Time!

Now call over one of the instructors or the TA to come look through your code and commit history! 
