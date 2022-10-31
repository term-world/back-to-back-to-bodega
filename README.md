
| Date              |          |
|:------------------|:---------|
| 31 October 2022 | Assigned |
| 6 November 2022    | Due      |
| Status            | See original `bodega` repository |

# BACK TO BUSINESS: "ENOUGH FUN AND GAMES," GRUMBLES MAYOR, "GO MAKE GOODS, GOODS, GOODS!"

**Reported by `Official Mayor-Endorsed News` on `31 October 2022`**

The only good `term-world` citizen is one who makes and consumes, makes and consumes forever. Riding an influx of quarters from neighborhood bodega games, slower sales in store goods have caused neighborhood economies to level off. Fortunately, the beast of capitalism always responds to more food and, as the Mayor commented during his recent direct-to-O.M.E.N "must run" dispatch: "that means _make stuff."

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

### Supporting media

[![YouTube thumbnail](http://img.youtube.com/vi/cJAXqu65W2s/hqdefault.jpg)](https://youtube.com/playlist?list=PLJvBsjwXNdlF99gvu4u3TIqBVk87xYirA)

## Accessing bodega Content

In order to complete the workload for the `bodega` you'll first need to `clone` the `bodega` repository into your `workshop`.

When you `clone` a repository you're duplicating its contents and adding them to your local workspace. Since you'll be working collaboratively with your neighbors, you'll each need your own copy of the `bodega` to work with.

In order to keep some of the magic (read: somewhat convoluted code) that makes `term-world` work the way it does, **you are required to clone all additional repositories within the `workshop`, located within your `garage`.**

Head to GitHub and:
* click on the green `Code` button
* ensure that `SSH` is selected
* copy the link that appears in the window below

It might look something like `git@github.com:term-world/bodega-Ix`.

Once you've copied this link, navigate to your terminal window and ensure you're still in the appropriate place (in this case, the topmost level of your `workshop`). Then, enter the command:

```
git clone COPIED-LINK-HERE
```

Be sure to replace the fragment `COPIED-LINK-HERE` with the link you copied. In the example regarding `bodega-Ix`, the full command would look like:

```
git clone git@github.com:term-world/bodega-Ix
```

While `pull` is used to *update* the contents of a repository that already exists in your local workspace, `clone` is used to *replicate* the contents of a repository from GitHub and copy them to your local workspace.

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

## Submitting `bodega` Content

Considering that the work you're doing for the `bodega` will be in a particular `branch` of the repository, there's a small adjustment that has to be made to our normal `add`, `commit`, `push` process.

When you're ready to push to GitHub, do the normal `add` and `commit` routines. Recall:

```
git add NAME_OF_FILE_OR_DIRECTORY_TO_ADD
```

You may need to do this for either:

* Individual files (i.e. `git add Thingamajig.py`)
* Directories (i.e. `git add Thingamajig`)

```
git commit -m "Descriptive commit message"
```

### Pushing to a branch

However, when it comes to push, run this slightly expanded command:

```
git push origin YOUR_BRANCH_NAME
```

We're still using `git push`, but this time we're adding an extra layer of information to the command; to be precise, we're specifically instructing `git` to push our changes to a particular branch of the repository (*your* branch). In the example regarding the `gadgets` department, the command to run would look like:

```
git push origin gadgets
```

### A "Pull Request"

Once you've completed this step, you'll now need to create a **pull request** on GitHub. This is a formal request to other collaborators on your project to review the code you've submitted--an important step when working together on the same project.

In a web browser, navigate to the repository page on GitHub (for the repository that you've just submitted new changes for). Towards the upper-left corner you'll see a dropdown that will have `main` selected as default (`main` being one of the branches for your repository, this is the "production-ready" branch). Select your branch from the dropdown, and you may see a yellow box prompting you to create a pull request; click that if you see it, or navigate to `Pull Requests` at the top and subsequently click the green `New pull request` button.

Now, in the top left corner select the branch you wish to add your updated changes to, or the "base" branch--generally speaking this will likely be `main`, the aforementioned "production-ready" branch. In the bar on the righthand side, add Reviewers to the pull request (this should be all of your neighborhood collaborators). Finally, click `Create pull request`.

You'll also be responsible for responding to and reviewing pull requests created by other collaborators on your team. Comment on each other's work about changes you'd like to see made to code submitted, and be sure to keep all communication both specific and professional.

## Merging `bodega` Content on GitHub

After all collaborators have had a chance to weigh in on a new pull request, if the work is up to snuff and ready to join the "production-ready" `main` branch, then your designated neighborhood team lead will have to merge that work into the `main` branch.

If you *are* said team lead, you'll need to navigate to the pull request on GitHub. If there are no "conflicts" (i.e., differences that can't be automatically handled by GitHub) between the pull request's branch and the `main` branch, simply click the `Commit merge` button and the merge is complete!

In some cases however, you'll have to specify what parts of a pull request make it into the `main` branch. If that's the case, you'll instead see a `Resolve conflicts` button. Click that and you'll be presented with a proposed merged copy of the code, with some extra lines added in. Something akin to:

```
<<<<<<
x = "this_is_a_line_of_code"
=======
x = "this_is_a_different_line_of_code"
>>>>>>
```

To resolve said conflicts, you'll need to delete the portion of code you don't want to appear in the final product, as well as any `<<<<<<`, `======`, or `>>>>>>` lines.

Once complete, click `Mark as resolved` followed by `Commit merge`, and the changes on the branch will be joined with the `main` branch!

## Updating `bodega` Content in Your Local Workspace

At some point you may wish to update the content in your local workspace with the changes being implemented by your teammates. 

To do so, `git checkout main` (or other collaborative branch) and run the command:

```
git pull
```

This will update your local workspace with the content stored in the `main` branch.

### `checkout` other folks' branches

It's _very_ likely that you'll run into the need to `checkout` a branch that GitHub has, but you don't. Here's a reminder of the steps to do that.

First, `fetch` all of the changes from the `remote` (GitHub):

```
git fetch --all
```

Once you've received this information, to `checkout` the `gadgets` branch (for example):

```
git checkout --track origin/gadgets
```

This will copy that branch from GitHub to your local workspace. You'll now also be able to `push` and `pull` to/from it.