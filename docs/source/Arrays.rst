Arrays
=====



What is an array? 
====

| An array is a list of items of a specific data type. 
| Each elements has a specific index assigned to it.

.. note::
    The first index of an array is actually 0, not 1.

| Here is a visual example. 
.. list-table:: Example array
    * - 0, "Hello"
    * - 1, "World!"
    * - 2, "Coding"
    * - 3, "is"
    * - 4, "cool."

| The above array would be the representation an array of strings

How to use an array in Java:
====

| You can declare an array like this
.. code-block:: java
    Type[] array = new Type[num_elements];


| Replace ``Type`` with a type such as a double or int, ``num_elements`` is a number which tells java the number of elements.
| The ``ArrayList<Type>`` 
