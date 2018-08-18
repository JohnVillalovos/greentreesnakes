Green Tree Snakes - the missing Python AST docs
===============================================

**Abstract Syntax Trees**, ASTs, are a powerful feature of Python. You can write
programs that inspect and modify Python code, after the syntax has been parsed,
but before it gets compiled to byte code. That opens up a world of possibilities
for introspection, testing, and mischief.

The `official documentation for the ast module <http://docs.python.org/3/library/ast>`_
is good, but somewhat brief. *Green Tree Snakes* is more like a field guide
(or should that be forest guide?) for working with ASTs. To contribute to the
guide, see the `source repository <https://bitbucket.org/takluyver/greentreesnakes>`_.

Contents:

.. toctree::
   :maxdepth: 2
   
   tofrom.rst
   nodes.rst
   manipulating.rst
   examples.rst

.. seealso::
   
   `Python AST explorer <https://python-ast-explorer.com/>`_
     Web-based AST viewer: paste some code in and see the AST

   `Thonny <http://thonny.org>`_
     A Python IDE with AST explorer built in (*Main menu => View => AST*)

   `showast <https://github.com/hchasestevens/show_ast>`_
     An IPython extension to show ASTs in Jupyter notebooks
   
   `Instrumenting the AST <http://www.dalkescientific.com/writings/diary/archive/2010/02/22/instrumenting_the_ast.html>`_
     Using AST tools to assess code coverage


Indices and tables
==================

* :ref:`genindex`
* :ref:`search`
