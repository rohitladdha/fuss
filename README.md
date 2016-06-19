# fuss: Benchmarking Tool
=========================

.. image:: https://img.shields.io/pypi/v/fuss.svg
    :target: https://pypi.python.org/pypi/fuss


Behold, the power of fuss:

.. code-block:: python

    # sample.py
    import fuss
    
    @fuss.measure
    def func():
      for i in range(100):
        pass
`Function: func took 0.00500679016113 ms`
                

Many programmers find it aversive to find time taken by function by using 
time module in a naive way. It becomes boring to measure time of similarly
other functions again and again. Fuss with a very simple implementation provides
and easy way for the same.

                    
Installation
------------

To install Requests, simply:

.. code-block:: bash

    $ pip install fuss
    ✨🍰✨

.. _`the repository`: http://github.com/rohitladdha/fuss
.. _AUTHORS: https://github.com/rohitladdha/requests/blob/master/AUTHORS.rst
.. _Contributor Friendly: https://github.com/rohitladdha/requests/issues?direction=desc&labels=Contributor+Friendly&page=1&sort=updated&state=open
