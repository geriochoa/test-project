.. Documentation master file, created by
   sphinx-quickstart on Wed Feb 14 12:20:02 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.


**************
RST is Simple!
**************

.. toctree::
   :maxdepth: 4
   :caption: Table of Contents:

   index

We can have sections:

This is a Section
==================

And continue nesting subsections if that is necessary for the organization of
the document structure.

Nested Subsection
_________________

Then we can do some simple formatting writing **bold** and *italics*, or we can
***combine*** them. The alternative of underscores does not work here.


Now, what about lists?. Well, we can have numbered lists:

1. First item
2. Second item
3. Third item

And bullet lists:

- First item
- Second item, which also happens to be a multi-line item.

  This is a new paragraph within the whole thing. Let's nest a list:

  1. This is a subitem
  2. And a second subitem

- And the list continues

But what if I wan automatic numbering. I can't be bothered with remembering
which item I'm currently writing. Let's try that then:

#. First item
#. Second item
#. Next item, whatever its number is
#. Another item

What About Code?
________________

Tow write inline code is simple `print("hello world")`. On the other hand, if
you want to write a block of code, try this::

  let x = 24;
  figure = new Figure("red");

  if (Figure.color === "red") {
     console.log("It is RED");
  }

It is also possible to try an explicit declaration.

.. code::

  let x = 24;
  figure = new Figure("red");

  if (Figure.color === "red") {
     console.log("It is RED");
  }

It is all nice and good but, what if I want my code to have some colors?. We
can do that too!:

.. code:: javascript

  let x = 24;
  figure = new Figure("red");

  if (Figure.color === "red") {
     console.log("It is RED");
  }

Cool!.

.. _hyperlinks:

Hyperlinks
__________

Well, we can add a `link to this <https://www.wizeline.com/>`_. We don't have
the other possibility of a link with title.

It is also possible to add `links using a reference`_. And links to arbitrary
text withing my document, like :ref:`the top of this section <hyperlinks>`.

.. _links using a reference: httpp://www.wizeline.com

Images
______

Images syntax is almost the same as links:

.. image:: https://i.imgur.com/QJCkuj6.jpg
   :width: 200px
   :height: 150px
   :align: center

A nice thing about RST is that it allows inline substitutions, very useful when
it comes to describing graphic interfaces and keyboard combinations.

.. |command| image:: _static/command-icon.png
   :align: middle
   :width: 12pt

To copy the text press `Command` |command| + `c`.

Tables
______

Well, tables may take a bit longer to typeset, they are slightly more flexible:

+------------+------------+-----------+
| Header 1   | Header 2   | Header 3  |
+============+============+===========+
| body row 1 | column 2   | column 3  |
+------------+------------+-----------+
| body row 2 | Cells may span columns.|
+------------+------------+-----------+
| body row 3 | Cells may  | - Cells   |
+------------+ span rows. | - contain |
| body row 4 |            | - blocks. |
+------------+------------+-----------+

Some other features
___________________

The `include` directive allows to *recycle* content.

There are also special directives for warnings, notes and pending tasks.

.. note::
  This is a note. Useful for reelevant information that a user must be aware of
  whe working with this software.


.. seealso:: 
  This is a sample of **seealso**, useful to highlight external links
  that complement your document

.. warning::
  A warning directive, to remark important things to keep in mind.

.. todo:: 
  This is a special directive that can be toggled on and off. It's purpose is
  to include notes for the writer, but those notes are not supposed to be part
  of the final document.




Indices and tables
==================

* :ref:`genindex`
* :ref:`search`
