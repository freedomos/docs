Updating your system
====================

Step 1: 
-------
Open your terminal. E.g. Konsole, Gnome-terminal, kitty, termite, allacritty etc.

Step 2: 
------

Pacman can update all packages on the system with just one command. This could take quite a while depending on how up-to-date the system is. 

The following command synchronizes the repository databases and updates the system's packages, excluding "local" packages that are not in the configured repositories:

.. code-block:: console
  pacman -Syu

more information on :doc:`Pacman` 
