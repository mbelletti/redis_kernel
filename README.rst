A simple IPython kernel for redis

This requires IPython 3, which is not yet released.

To test it, install with ``setup.py``, then::

    ipython qtconsole --kernel redis

For details of how this works, see IPython's docs on `wrapper kernels
<http://ipython.org/ipython-doc/dev/development/wrapperkernels.html>`_, and

This connects to redis using sockets, so you dont need the redis python client