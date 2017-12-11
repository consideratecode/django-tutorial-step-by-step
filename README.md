A step-by-step solution for the official Django tutorial
========================================================
This repository contains the Django project you build in the official
Django tutorial: the `mysite` project with the `polls` app.

Each commit corresponds to a step in the tutorial.

If you get stuck while following the tutorial, you can check what your
code should look like - right at the step you are currently at.

For further motivation, visit https://consideratecode.com/2017/12/15/django-tutorial-step-by-step

How this repository is structured
---------------------------------
There is a tagged commit for each complete code change. The commit message
indicated which step of the tutorial the commit refers to.

In most cases, each commit corresponds to the state of your project *after* a
single section or sub-section in the tutorial.

Sometimes, a section contains multiple code changes that you should try one
after the other, e.g. the section ["Customize the admin change list"](https://docs.djangoproject.com/en/2.0/intro/tutorial07/#customize-the-admin-change-list) in Part 7
corresponds to five commits.

Table of contents:
------------------
Here is a list of all steps in the tutorial, linked to the corresponding tag. The name of each tag is shown in brackets.

Part 1:
* [Part 1: Creating a project](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/1.1) [2.0/1.1]
* [Part 1: Creating the Polls app](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/1.2) [2.0/1.2]
* [Part 1: Writing your first view](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/1.3) [2.0/1.3]

Part 2:
* [Part 2: Database setup](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/2.1) [2.0/2.1]
* [Step 2: Creating models](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/2.2) [2.0/2.2]
* [Part 2: Activating models](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/2.3) [2.0/2.3]
* [Part 2: Playing with the API](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/2.4) [2.0/2.4]
* [Part 2: Introducing the Django Admin](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/2.5) [2.0/2.5]

Part 3:
* [Part 3: Writing more views](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/3.1) [2.0/3.1]
* [Part 3: Write views that actually do something](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/3.2) [2.0/3.2]
* [Part 3: Write views that actually do something - with templates](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/3.2.1) [2.0/3.2.1]
* [Part 3: Write views that actually do something - A shortcut: render()](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/3.2.2) [2.0/3.2.2]
* [Part 3: Raising a 404 error](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/3.3.1) [2.0/3.3.1]
* [Part 3: Raising a 404 error - A shortcut: get_object_or_404()](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/3.3.2) [2.0/3.3.2]
* [Part 3: Use the template system](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/3.4) [2.0/3.4]
* [Part 3: Removing hardcoded URLs in templates](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/3.5) [2.0/3.5]
* [Part 3: Namespacing URL names](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/3.6) [2.0/3.6]

Part 4
* [Part 4: Write a simple form](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/4.1.1) [2.0/4.1.1]
* [Part 4: Write a simple form - results view](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/4.1.2) [2.0/4.1.2]
* [Part 4: Use generic views: Less code is better](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/4.2) [2.0/4.2]

Part 5:
* [Part 5: Writing our first test - Create a test to expose the bug](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/5.1.1) [2.0/5.1.1]
* [Part 5: Writing our first test - Fixing the bug](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/5.1.2) [2.0/5.1.2]
* [Part 5: Writing our first test - More comprehensive tests](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/5.1.3) [2.0/5.1.3]
* [Part 5: Test a view - Improving our view](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/5.2.1) [2.0/5.2.1]
* [Part 5: Test a view - Testing our new view](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/5.2.2) [2.0/5.2.2]
* [Part 5: Test a view - Testing the DetailView](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/5.2.3) [2.0/5.2.3]

Part 6:
* [Part 6: Customize your app’s look and feel](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/6.1) [2.0/6.1]
* [Part 6: Adding a background-image](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/6.2) [2.0/6.2]

Part 7:
* [Part 7: Customize the admin form - reordering the fields](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/7.1.1) [2.0/7.1.1]
* [Part 7: Customize the admin form - split the form](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/7.1.2) [2.0/7.1.2]
* [Part 7: Adding related objects - register Choice with the admin](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/7.2.1) [2.0/7.2.1]
* [Part 7: Adding related objects - remove Choice from admin, add inline](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/7.2.2) [2.0/7.2.2]
* [Part 7: Adding related objects - use TabularInline (instead of StackedInline)](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/7.2.3) [2.0/7.2.3]
* [Part 7: Customize the admin change list - use list_display option](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/7.3.1) [2.0/7.3.1]
* [Part 7: Customize the admin change list - include was_published_recently()](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/7.3.2) [2.0/7.3.2]
* [Part 7: Customize the admin change list - add attributes to was_published_recently()](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/7.3.3) [2.0/7.3.3]
* [Part 7: Customize the admin change list - add list_filter](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/7.3.4) [2.0/7.3.4]
* [Part 7: Customize the admin change list - add search_fields](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/7.3.5) [2.0/7.3.5]
* [Part 7: Customize the admin look and feel - Customizing your project’s templates](https://github.com/consideratecode/django-tutorial-step-by-step/tree/2.0/7.4) [2.0/7.4]

If you want to check out the code at a specific step, simply checkout the tag.
E.g. if you are stook in "Part 6: Customize your app’s look and feel", do the
following:

    $ git clone git@github.com:consideratecode/django-tutorial-step-by-step.git
    $ cd django-tutorial-step-by-step
    $ git checkout 2.0/6.1

This repository does intentionally not contain:

* `__pycache__` directories containing Python bytecode
* the file `db.sqlite3` containing the SQLite database



Contributing
------------
If you find any mistakes, open an issue or create a pull request. If you are
unsure how to do that, drop me an email.

My goal is to stay true to the idea of one commit per step in the tutorial.
This means that I will probably have to change tags and branch names if
any changes are made.


Author
------
Daniel Hepper <daniel@consideratecode.com>


License and Copyright
---------------------
The code in this repository originates from the Django tutorial, released
as part of Django under the Modified BSD License by the Django Software
Foundation and individual contributors. My original contribution to this
repository is essentionally this README. For the full terms, see LICENSE.

The name "Django" is a registered trademark of the Django Software Foundation.
Please note that any references to the official Django tutorial
are nominative and should not imply affiliation with or endorsement by the
Django Software Foundation.
