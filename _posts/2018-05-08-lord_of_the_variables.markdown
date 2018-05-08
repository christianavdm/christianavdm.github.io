---
layout: post
title:      "Lord of the Variables"
date:       2018-05-08 22:47:37 +0000
permalink:  lord_of_the_variables
---


ICYMI: [Lord of the Rings summary](https://www.youtube.com/watch?v=_2mDlfe3yl4)

If the entire Lord of the Rings universe existed on a program inside my computer, one of the less interesting things that I could do would be to write a blog post illustrating different types of Ruby variables, as used in the LOTR program. 

This post explores five types of Ruby variables: 
* Local
* Instance
* Class
* Global
* Constant


**Local Variable**

```
the_shire = "A local variable starts with a lowercase letter or underscore" 
```

![The Shire](http://images6.fanpop.com/image/photos/33400000/The-Shire-the-shire-33427044-600-382.jpghttp://)

Local variables have the smallest scope. They can only be accessed within the code construct where they were declared. For example, if a local variable is declared within a method, it can only be referenced or used within that method. 

In our Lord of the Rings universe, a local variable represents a single area of Middle Earth, like the Shire. You can't access the Shire from Gondor; you need to travel back to the Shire. 

**Instance Variable**

```
@lotr_character = "An instance variable starts with @"
```

![LOTR characters](http://middleearthnews.com/files/2012/09/i-am-no-bro-300x257.jpeghttp://)

Instance variables have a broader scope than local variables. They can be accessed anywhere within the class where they were declared. Their values are specific to an instance. 

The characters in Lord of the Rings are represented by an instance variable. They are all individual people (or hobbits, elves, etc.) that are instances who play a role in the universe. 

**Class Variable**

```
@@the_fellowship = "A class variable starts with @@" 
```

![The Fellowship of the Ring](https://www.pinterest.com/kellhalpin/gimli-certainty-of-death-small-chance-of-success-w/http://)

Class variables are the same as instance variables in that they can be accessed anywhere within the class where they were declared. However, their values do not change from instance to instance. 

How could Middle Earth be saved without the Fellowship of the Ring? And how could we create a Fellowship without a class variable? The class variable @@the_fellowship maintains a list of all the characters who are a part of the Fellowship. 

**Global Variable**

```
$im_a_global_variable = "A global variable starts with $" 
```

![One Ring to rule them all](https://www.gundersons.com/blog/wp-content/uploads/2017/08/lordoftherings-ring-map.jpghttp://)

The scope of global variables is the entire program, just like the area of influence for the One Ring is the entire Middle Earth. And like the One Ring, you generally just shouldn't touch global variables. 


**Constant**

```
Im_a_constant = "A constant starts with a capital letter"
```

![The ring must be destroyed.](https://memegenerator.net/img/instances/59088811.jpghttp://)

The value of a constant should not change. It's like the driving mission of the entire LOTR story: *the Ring must be destroyed*. That mission doesn't change throughout our LOTR universe. 






