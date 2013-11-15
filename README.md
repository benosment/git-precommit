git-precommit
=============

Hooks for git precommit


How to add precommit hooks
--------------------------
Copy one of the precommit scripts to the hooks subdirectory of the
Git directory:

Example:
 $ cp python-precommit .git/hooks/pre-commit


Types of hooks:
---------------
 * python-precommit: run PEP8 style checker 
   - requires flake8 (sudo apt-get install python-flake8)
