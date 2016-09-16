
.. _jupyter:

=============================================================
Jupyter notebooks
=============================================================

See :ref:`software` for information on installing Jupyter notebooks.

Python is the default language if you start a new notebook.

.. _pymatbridge:

Using Matlab in notebooks
-------------------------

If you want to type Matlab code in a cell and execute that cell using Matlab,
you can use `Pymatbridge <https://arokem.github.io/python-matlab-bridge/>`_ so
that a cell that starts with the ``magic command'' `%%matlab` will be executed
in Matlab.

If you install Pymatbridge and also the `Matlab kernel extension
<https://pypi.python.org/pypi/matlab_kernel>`_ then you can create a notebook
that runs the Matlab kernel as the default for all cells.
Then you do not need to start cells with
`%%matlab`.  (In this case you can start a cell with `%%python` if you want
one cell to use Python instead.)

You should be able to get both `pymatbridge` and `matlab_kernel` via::

    pip install matlab_kernel

If you don't have the Python package manager `pip` but have the Anaconda
Python, try::

    conda install pip
