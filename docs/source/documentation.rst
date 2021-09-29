Documentation Table of Content
=====

.. _installation:

Overview
------------

To use Lumache, first install it using pip:

.. code-block:: console

   (.venv) $ pip install lumache

Guidelines
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

Product Knowledge
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:
