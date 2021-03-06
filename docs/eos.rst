
Equations of State
=========================================================

Here we list list the available equations of state and the function used to access them. 

.. autofunction:: despasito.equations_of_state.eos


.. _eos-types:

Available EOS
-------------

.. toctree::
   :maxdepth: 1

   saft_gamma_mie
   peng-robinson


Adding an EOS
-------------

Adding an EOS family is easily implemented by adding a new directory to the ``equations_of_state`` directory. A new EOS is then added by adding a module with the desired EOS inside that is derived from our EOS interface (shown below).

.. note:: In the future, a USER folder will be included in our program so that users can collect all of their personal additions and modifications to DESPASITO in one location.

.. automodule::
   despasito.equations_of_state.interface
   :members:


