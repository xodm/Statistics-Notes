A few things i learned in this chapter

- They expect you to download their software, *sur*
- You use `?NELS` to get some sort of index of their data.
- If you do `str(NELS)` you get a string version of all the data given, you are able to see the variables and the types.
- To see the list of one of its varibles, you do `NELS$variable`
- You can use `dim(NELS)` to get their dimension.
- Just like a list in python, you can use `NELS$VAR[NELS$id==1]`. Okay, i am assuming each variable was given some sort of id, you can think of it like a discord id, and this is how i am able to get the person i want `NELS$VAR[personIWant]`.
- == is used as equal, obv.

__NEXT STEP WAS EVEN COOLER, WE DID HOW TO USE A CSV__

Which by the way is comma-separated values.

Okay, got to excel, make your own list, the name of the file will be the header and what not. Go to file > export > save as csv
now, you will go to R and do `the_var_name = read.csv (file.choose(), header = T)`, this will open up a browser which will let you pick the file.

