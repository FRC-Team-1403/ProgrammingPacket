Basic Types
=====

a ``char`` can be used to represent a single character.
an ``int`` type represents an whole number which can be either positive or negative.
a ``float`` or ``double`` can be used to represent a number with decimals. 
a ``String`` type can be used to store sentences and words.

.. note::
    | Consider the following:
    | int a = 2; int b = 3;
    | int c = a/b;
    | You would expect c to be 1 because of rounding, but c is actually equal to 0.
    | This is caused by integer truncation when divding; The computer will chop off the decmials.
    | Using a float or double or casting to one of these will resolve the issue.

Casting can be done like this: ``float num = (float) int_num``, what you are doing here is converting one type to another. 

Programming Challenges:  
#. Input 2 numbers and divide them, print the result (make sure to try 1/2)
#. 
