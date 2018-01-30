Simple Notebook Example
=======================

This provides a notebook that demonstrates the different
features available in the `sphinxcontrib.jupyter <https://github.com/QuantEcon/sphinxcontrib-jupyter>`__
extension.

Text will appear as a markdown cell in the notebook split by code-blocks. 

To add a code block you can use ``code-block`` directives such as:

.. code-block:: python3

    import quantecon as qe

Math will flow through to the Jupyter notebook and will be rendered in place by mathjax

.. math::

    \mathbb P\{z = v \mid x \}
    = \begin{cases} 
        f_0(v) & \mbox{if } x = x_0, \\
        f_1(v) & \mbox{if } x = x_1
    \end{cases} 

