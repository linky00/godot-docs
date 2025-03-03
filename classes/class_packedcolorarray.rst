:github_url: hide

.. Generated automatically by doc/tools/make_rst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the PackedColorArray.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_PackedColorArray:

PackedColorArray
================

A packed :ref:`Array<class_Array>` of :ref:`Color<class_Color>`\ s.

Description
-----------

An :ref:`Array<class_Array>` specifically designed to hold :ref:`Color<class_Color>`. Packs data tightly, so it saves memory for large array sizes.

Constructors
------------

+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`PackedColorArray<class_PackedColorArray>` | :ref:`PackedColorArray<class_PackedColorArray_constructor_PackedColorArray>` **(** **)**                                                      |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`PackedColorArray<class_PackedColorArray>` | :ref:`PackedColorArray<class_PackedColorArray_constructor_PackedColorArray>` **(** :ref:`PackedColorArray<class_PackedColorArray>` from **)** |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`PackedColorArray<class_PackedColorArray>` | :ref:`PackedColorArray<class_PackedColorArray_constructor_PackedColorArray>` **(** :ref:`Array<class_Array>` from **)**                       |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------+

Methods
-------

+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`                         | :ref:`append<class_PackedColorArray_method_append>` **(** :ref:`Color<class_Color>` value **)**                                         |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------+
| void                                            | :ref:`append_array<class_PackedColorArray_method_append_array>` **(** :ref:`PackedColorArray<class_PackedColorArray>` array **)**       |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`                           | :ref:`bsearch<class_PackedColorArray_method_bsearch>` **(** :ref:`Color<class_Color>` value, :ref:`bool<class_bool>` before=true **)**  |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`PackedColorArray<class_PackedColorArray>` | :ref:`duplicate<class_PackedColorArray_method_duplicate>` **(** **)**                                                                   |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------+
| void                                            | :ref:`fill<class_PackedColorArray_method_fill>` **(** :ref:`Color<class_Color>` value **)**                                             |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`                         | :ref:`has<class_PackedColorArray_method_has>` **(** :ref:`Color<class_Color>` value **)** |const|                                       |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`                           | :ref:`insert<class_PackedColorArray_method_insert>` **(** :ref:`int<class_int>` at_index, :ref:`Color<class_Color>` value **)**         |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`                         | :ref:`is_empty<class_PackedColorArray_method_is_empty>` **(** **)** |const|                                                             |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`                         | :ref:`push_back<class_PackedColorArray_method_push_back>` **(** :ref:`Color<class_Color>` value **)**                                   |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------+
| void                                            | :ref:`remove_at<class_PackedColorArray_method_remove_at>` **(** :ref:`int<class_int>` index **)**                                       |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`                           | :ref:`resize<class_PackedColorArray_method_resize>` **(** :ref:`int<class_int>` new_size **)**                                          |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------+
| void                                            | :ref:`reverse<class_PackedColorArray_method_reverse>` **(** **)**                                                                       |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------+
| void                                            | :ref:`set<class_PackedColorArray_method_set>` **(** :ref:`int<class_int>` index, :ref:`Color<class_Color>` value **)**                  |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`                           | :ref:`size<class_PackedColorArray_method_size>` **(** **)** |const|                                                                     |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`PackedColorArray<class_PackedColorArray>` | :ref:`slice<class_PackedColorArray_method_slice>` **(** :ref:`int<class_int>` begin, :ref:`int<class_int>` end=2147483647 **)** |const| |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------+
| void                                            | :ref:`sort<class_PackedColorArray_method_sort>` **(** **)**                                                                             |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`PackedByteArray<class_PackedByteArray>`   | :ref:`to_byte_array<class_PackedColorArray_method_to_byte_array>` **(** **)** |const|                                                   |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------+

Operators
---------

+-------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`                         | :ref:`operator !=<class_PackedColorArray_operator_neq_bool>` **(** **)**                                                                  |
+-------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`                         | :ref:`operator !=<class_PackedColorArray_operator_neq_bool>` **(** :ref:`PackedColorArray<class_PackedColorArray>` right **)**            |
+-------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`PackedColorArray<class_PackedColorArray>` | :ref:`operator +<class_PackedColorArray_operator_sum_PackedColorArray>` **(** :ref:`PackedColorArray<class_PackedColorArray>` right **)** |
+-------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`                         | :ref:`operator ==<class_PackedColorArray_operator_eq_bool>` **(** **)**                                                                   |
+-------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`                         | :ref:`operator ==<class_PackedColorArray_operator_eq_bool>` **(** :ref:`PackedColorArray<class_PackedColorArray>` right **)**             |
+-------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Color<class_Color>`                       | :ref:`operator []<class_PackedColorArray_operator_idx_Color>` **(** :ref:`int<class_int>` index **)**                                     |
+-------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------------+

Constructor Descriptions
------------------------

.. _class_PackedColorArray_constructor_PackedColorArray:

- :ref:`PackedColorArray<class_PackedColorArray>` **PackedColorArray** **(** **)**

Constructs an empty ``PackedColorArray``.

----

- :ref:`PackedColorArray<class_PackedColorArray>` **PackedColorArray** **(** :ref:`PackedColorArray<class_PackedColorArray>` from **)**

Constructs a ``PackedColorArray`` as a copy of the given ``PackedColorArray``.

----

- :ref:`PackedColorArray<class_PackedColorArray>` **PackedColorArray** **(** :ref:`Array<class_Array>` from **)**

Constructs a new ``PackedColorArray``. Optionally, you can pass in a generic :ref:`Array<class_Array>` that will be converted.

Method Descriptions
-------------------

.. _class_PackedColorArray_method_append:

- :ref:`bool<class_bool>` **append** **(** :ref:`Color<class_Color>` value **)**

Appends an element at the end of the array (alias of :ref:`push_back<class_PackedColorArray_method_push_back>`).

----

.. _class_PackedColorArray_method_append_array:

- void **append_array** **(** :ref:`PackedColorArray<class_PackedColorArray>` array **)**

Appends a ``PackedColorArray`` at the end of this array.

----

.. _class_PackedColorArray_method_bsearch:

- :ref:`int<class_int>` **bsearch** **(** :ref:`Color<class_Color>` value, :ref:`bool<class_bool>` before=true **)**

Finds the index of an existing value (or the insertion index that maintains sorting order, if the value is not yet present in the array) using binary search. Optionally, a ``before`` specifier can be passed. If ``false``, the returned index comes after all existing entries of the value in the array.

\ **Note:** Calling :ref:`bsearch<class_PackedColorArray_method_bsearch>` on an unsorted array results in unexpected behavior.

----

.. _class_PackedColorArray_method_duplicate:

- :ref:`PackedColorArray<class_PackedColorArray>` **duplicate** **(** **)**

Creates a copy of the array, and returns it.

----

.. _class_PackedColorArray_method_fill:

- void **fill** **(** :ref:`Color<class_Color>` value **)**

Assigns the given value to all elements in the array. This can typically be used together with :ref:`resize<class_PackedColorArray_method_resize>` to create an array with a given size and initialized elements.

----

.. _class_PackedColorArray_method_has:

- :ref:`bool<class_bool>` **has** **(** :ref:`Color<class_Color>` value **)** |const|

Returns ``true`` if the array contains ``value``.

----

.. _class_PackedColorArray_method_insert:

- :ref:`int<class_int>` **insert** **(** :ref:`int<class_int>` at_index, :ref:`Color<class_Color>` value **)**

Inserts a new element at a given position in the array. The position must be valid, or at the end of the array (``idx == size()``).

----

.. _class_PackedColorArray_method_is_empty:

- :ref:`bool<class_bool>` **is_empty** **(** **)** |const|

Returns ``true`` if the array is empty.

----

.. _class_PackedColorArray_method_push_back:

- :ref:`bool<class_bool>` **push_back** **(** :ref:`Color<class_Color>` value **)**

Appends a value to the array.

----

.. _class_PackedColorArray_method_remove_at:

- void **remove_at** **(** :ref:`int<class_int>` index **)**

Removes an element from the array by index.

----

.. _class_PackedColorArray_method_resize:

- :ref:`int<class_int>` **resize** **(** :ref:`int<class_int>` new_size **)**

Sets the size of the array. If the array is grown, reserves elements at the end of the array. If the array is shrunk, truncates the array to the new size.

----

.. _class_PackedColorArray_method_reverse:

- void **reverse** **(** **)**

Reverses the order of the elements in the array.

----

.. _class_PackedColorArray_method_set:

- void **set** **(** :ref:`int<class_int>` index, :ref:`Color<class_Color>` value **)**

Changes the :ref:`Color<class_Color>` at the given index.

----

.. _class_PackedColorArray_method_size:

- :ref:`int<class_int>` **size** **(** **)** |const|

Returns the number of elements in the array.

----

.. _class_PackedColorArray_method_slice:

- :ref:`PackedColorArray<class_PackedColorArray>` **slice** **(** :ref:`int<class_int>` begin, :ref:`int<class_int>` end=2147483647 **)** |const|

Returns the slice of the ``PackedColorArray``, from ``begin`` (inclusive) to ``end`` (exclusive), as a new ``PackedColorArray``.

The absolute value of ``begin`` and ``end`` will be clamped to the array size, so the default value for ``end`` makes it slice to the size of the array by default (i.e. ``arr.slice(1)`` is a shorthand for ``arr.slice(1, arr.size())``).

If either ``begin`` or ``end`` are negative, they will be relative to the end of the array (i.e. ``arr.slice(0, -2)`` is a shorthand for ``arr.slice(0, arr.size() - 2)``).

----

.. _class_PackedColorArray_method_sort:

- void **sort** **(** **)**

Sorts the elements of the array in ascending order.

----

.. _class_PackedColorArray_method_to_byte_array:

- :ref:`PackedByteArray<class_PackedByteArray>` **to_byte_array** **(** **)** |const|

Operator Descriptions
---------------------

.. _class_PackedColorArray_operator_neq_bool:

- :ref:`bool<class_bool>` **operator !=** **(** **)**

----

- :ref:`bool<class_bool>` **operator !=** **(** :ref:`PackedColorArray<class_PackedColorArray>` right **)**

----

.. _class_PackedColorArray_operator_sum_PackedColorArray:

- :ref:`PackedColorArray<class_PackedColorArray>` **operator +** **(** :ref:`PackedColorArray<class_PackedColorArray>` right **)**

----

.. _class_PackedColorArray_operator_eq_bool:

- :ref:`bool<class_bool>` **operator ==** **(** **)**

----

- :ref:`bool<class_bool>` **operator ==** **(** :ref:`PackedColorArray<class_PackedColorArray>` right **)**

----

.. _class_PackedColorArray_operator_idx_Color:

- :ref:`Color<class_Color>` **operator []** **(** :ref:`int<class_int>` index **)**

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
