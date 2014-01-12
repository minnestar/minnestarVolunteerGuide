MinneStarVolunteerGuide
=======================

The docbook 5 source for the Minnestar Volunteer Guide

Why?
----

This book was stared to create a central source of information for our volunteers.

How To Build
------------

This work was built upon the Short Attention Span Docbook work by @napcs which makes building a book that you can format into different formats super easy. To get started you will need to take a look at the documentation on http://napcs.com/products/docbook/ or at the source repository at https://
github.com/napcs/docbook. Please take time to pull down the framework and set it up per the provided instructions.

After you have gotten the framework pulled down and set up you will need to clone this repoistory to your local system.

Make sure that your ENV variable for SHORT_ATTENTION_SPAN_DOCBOOK_PATH is set to the path of the docbook that you installed above.

Go into the cloned directory.

To generate a pdf file:
'''rake book.pdf'''