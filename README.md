
| Date              |          |
|:------------------|:---------|
| TODO | Assigned |
| ODO   | Due      |
| Status            | See original `bodega` repository |

# BACK TO BUSINESS: "ENOUGH FUN AND GAMES," GRUMBLES MAYOR, "GO MAKE GOODS, GOODS, GOODS!"

**Reported by `Official Mayor-Endorsed News` on `TODO`**

The only good `term-world` citizen is one who makes and consumes, makes and consumes forever. Riding an influx of quarters from neighborhood bodega games, slower sales in store goods have caused neighborhood economies to level off. Fortunately, the beast of capitalism always responds to more food and, as the Mayor commented during his recent direct-to-O.M.E.N "must run" dispatch: "that means _make stuff_."

Neighborhoods all over `term-world` are expected to rally to the cause: can they create consumer goods to capture the most currency possible? While only time will tell, the variety of bodega departments is promising. During an interview scheduled with a citizen taken from the Mayor's approved interview list, one `term-world` citizen confessed, "I like stuff."

How will this wave of consumer choice affect the city? Will the next `Couch.py`, `Groomba`, or `Sandwich.py` emerge from the neighborhoods of `term-world`? The Mayor certainly hopes so. Conducting his latest interview from a room filled with alligator and termite plushies, he urged citiezens to make more meaningless goods: "look at all this stuff! Isn't it great? It has absolutely no meaning, and trust me, my citizens, that's for, as I--your Mayor know--the best."

## Overview

**This assignment must be completed in your neighborhood's original `bodega` repository -- not here!**

In this activity, you'll:

* discover what a `module` really is by writing your own
* learn how to import custom self-written `modules` into code
* begin exploring object-oriented principles in Python

To achieve this, we need to:

* define behaviors of our department objects
* create the `use` case for each of the objects and invoke it in a `main` function
* ensure that `Counter.py` displays:
  * descriptions of department goods using their `__str__` "magic" function
    * `function`s surrounded by `__` are also known as "dunder"s
  * the planned price of your prospective goods
    * this will require creating a `property` of the items called `price`

_If_ all of this is done correctly, you should be able to "pick up" these items _and_ see their catalog prices printed in the _new, improved_ readout of `Counter.py`!

## Supporting media

[![YouTube thumbnail](http://img.youtube.com/vi/cJAXqu65W2s/hqdefault.jpg)](https://youtube.com/playlist?list=PLJvBsjwXNdlF99gvu4u3TIqBVk87xYirA)

### Previous Learning Objectives

If you wish to review previous learning objectives from our assignments, you can visit the [`Syllabus`](https://chompe.rs/100-syllabus) for helpful information. However, it's also important to make an effort to retain what we have covered thus far as we progress through the course sections of the Readme might be taken out.

## Completing `bodega` content

### Items

For this activity, you'll need to complete the following steps for all of your `bodega` items, making them finally _animate_:

* plan functionality for each
  * for example: clothing might ask for a user size and print that size as part of their `__str__` method.
* **rename** your item files such that they contain no `.`, `'`, `<`, `&`, or other non-alphanumeric characters
* add `__str__` and `use` methods for each item such that:
  * you can _instantiate_ (create) and invoke each  item from an _external_ `main` in _each_ file (we'll do this together in class)
  * keep in mind that all `__str__` and `use` methods should take _at least_ the _implicit_ self-knowledge parameter
* add a `price` property to your items in the appropriate location (i.e. the _constructor_)
* create a `main` function for your items which:
  * _instantiates_ instances of your item
  * `print`s your item's `__str__` value
  * calls the `use` method to test that the item's functionality works

You will need to do this for _each_ `*.py` file in your given department. 

#### Note

The items in your `bodega` departments are _consumable_, meaning tha they are used up once they run. (i.e. they _delete_ themselves). To avoid losing your source code, you need to use the `term-world` inventory system. To see what you have (you already have some things), type `inventory` at your command prompt. This displays a table of what you already have in hand.

* To "pick up" a new item to test it, type `get FILE_NAME.py`
  * Be sure you're in the same folder as that thing
* To test the item (i.e. `use` it), type `use FILE_NAME`
  * Note that the `*py` is missing here

## Improvement Suggestions

Here are some suggestions for improvements you can use:

|Improvement Suggestions |Description        |
|:--------------------|:------------------|
|Classes/Methods|	Add additional functionality to the use() function of bodega goods|
|Conditional Logic|	Shopping guide for department of bodega; help shoppers choose what to buy|
|Dictionaries|	Add bodega inventory to Counter; track how many of each good is in stock   |   
|||
|||
|||
|||
|||
|||
|||

**Make sure to link your issue with the pull request you used to make your actually improvement.**

**If you are not following an improvement suggestion you need to have your improvement suggestion checked by the professor before proceeding.**
  
## Backup Policy Reminder

**While we may use this server to store code, you are responsible for using GitHub as your main backup.**

In the event that the `term-world` server goes down for any unforeseen reason, your work may be lost. Though this server is backed up on a regular (i.e. weekly) basis, there is no guarantee that up-to-the-minute data for your work will be restored.

Remember: to err is human; to back up your work is *divine*.
