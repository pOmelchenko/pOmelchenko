.. test documentation master file, created by
   sphinx-quickstart on Sat Jul  8 14:19:03 2023.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to test's documentation!
================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

.. sourcecode:: ini

   [mcu]
   ololo: trololo

This is a normal text paragraph. The next paragraph is a code sample::

   It is not processed in any way, except
   that the indentation is removed.

   It can span multiple lines.

This is a normal text paragraph again.

.. mermaid::

   sequenceDiagram
      participant Alice
      participant Bob
      Alice->John: Hello John, how are you?
      loop Healthcheck
          John->John: Fight against hypochondria
      end
      Note right of John: Rational thoughts <br/>prevail...
      John-->Alice: Great!
      John->Bob: How about you?
      Bob-->John: Jolly good!

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
