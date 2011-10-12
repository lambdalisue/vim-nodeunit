************************
 nodeunit.vim
************************

A simple compiler for executing nodeunit_ on VIM. Useful to use with vim-makegreen_

See http://blog.staz.be/?post/2010/09/04/Python-unit-test-and-vim for how to use this compiler with vim-makegreen_. It is not exactly its tutorial but really compatible.

.. _nodeunit: https://github.com/caolan/nodeunit
.. _vim-makegreen: https://github.com/reinh/vim-makegreen

how to install
============================
use vundle_ or pathogen_ is recommended or simply extract to your vim directory

.. _vundle: https://github.com/gmarik/vundle
.. _pathogen: http://www.vim.org/scripts/script.php?script_id=2332

and write the following code to your ``ftplugin/javascript.vim`` or ``ftplugin/coffee.vim``::

    set compiler=nodeunit



