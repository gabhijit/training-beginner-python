The ``Division`` Class
======================

A division class is a simple class which does something very simple, given
two numbers - numerator and denominator, it can perform division of the two
numbers -

Thus to create objects of the ``Division`` class, we'll need two values -
A numerator and a denominator.

Let's learn what is "Object" - An object is just something stored in a
computer memory and given a name. We'll soon see how it can be useful.

An object has got - state and actions.

What is 'state' ? State is some
collection of attributes of - objects. The attributes can be simple Python
built-in types like ``str``, ``int`` etc. or built-in data structures like -
``list``, ``dict``, ``set`` etc.

What are actions?
Actions are method defined within an object - The syntax is very similar to
the way methods are defined except some additional constraints -

The following code defines a division class with it's state corresponding to -
numerator and denominator and having only one action - ``perform_division``,
that performs actual division and returns the result of that division.


.. code::
   :language: python
   :linenos:

    class Division:

        def __init__(self, numerator, denominator):
            self.numerator = numerator
            self.denominator = denominator

        def perform_division(self):

            return numerator / denominator

This is back to normal. Let's look in more details at code above -

