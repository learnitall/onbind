onbind
======

.. image:: https://mybinder.org/badge.svg 
   :target: https://mybinder.org/v2/gh/learnitall/onbind/master?urlpath=lab

Online development environment using Binder and Jupyter notebooks. 

**This branch is for working through the Udemy course `Python for Data Science
and Machine Learning Bootcamp <https://www.udemy.com/python-for-data-science-and-machine-learning-bootcamp/learn/v4/overview>`_.**


What's this about?
------------------

There are always those times where we find ourselves with a bit of free time for some 
development and without a proper system and/or environment to do so. The goal with this
repository is to have a ready-to-go and persistent environment for Python development. 
Whether its working through a `Udemy <https://udemy.com>`_ course, chunking through a large 
project or just messing around, this repo is setup to facilitate it for free.


Who is this for?
----------------

This is really just meant for personal use, however feel free to fork it or use the same 
structure for your own environment. Note though that becaues this is for personal development,
exploration and brainstorming, commits made will probably be ugly and works in progress. 


How does it work?
-----------------

`Binder <https://mybinder.org>`_ is used to turn the Jupyter notebooks hosted in
this repository into a full on development environment (you can read about how
it works in their `documentation <https://mybinder.readthedocs.io/en/latest/>`_).
When changes are made to notebooks inside of the Binder-created environment, they
are manually commited back into the repository and as a result, the evironment 
gets refreshed automatically. This allows all code to be hosted on GitHub and edited 
through a web-browser.


How is it structured?
---------------------

Each project is organized into its own branch, with the master branch acting as a template
for creating new projects. This was done to allow for the segmentation of commits and 
dependencies and to give each project its own URL (Binder links environments based
on their branch). 


License
-------

See `LICENSE <https://github.com/learnitall/onbind/blob/master/LICENSE>`_.

