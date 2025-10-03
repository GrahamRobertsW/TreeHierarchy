TreeHierarchy
Graham Roberts
grahamrobertsw@gmail.com
Code for creating a Hierarchiucal classifier

This is a very early version of the code.
It is lacking some functionality, most notably mechanisms for programatically defining the structure.
This code also contains some additional functionality such as kernel ridge regression options in the decoder.
This is tied to a particular application.
In the future this will wither be expanded to include full classification and regression functionality, or more notable this functionality will splinter into a separate more appropriately purposed module.
The basis of this code is the TreeHierarchy class.

#TreeHierarchy
This is a recursive class, similar to a decision tree, albeit with a few distinct differences. 
The most important distinction is that instead of splitting at each node based on a random selection of features, an independedntly tuned and trained binary classifier is present at each juntion.
This 
