==============
Name My Sprint
==============

This project will generate the name of your team's next sprint by
combining a random adjective and a random name. There is a support
for several name packs - for example cyclists, star wars characters, ...

Installation
============

The latest stable release can be installed from PyPI:

.. code-block:: console

    $ pip install namemysprint

Or if you're feeling adventurous and want to install from source:

.. code-block:: console

    $ pip install .

Usage
=====

Once installed, run the included script to get a sprint name:

.. code-block:: console

    $ name-my-sprint
    Your next sprint should be called Thirsty Cavendish.


Or select the specific name pack you're interested in:
 
.. code-block:: console

    $ name-my-sprint --name-pack starwars
    Your next sprint should be called Eloquent Windu.
