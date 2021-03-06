.. _install:

=====================================
Installation, testing and development
=====================================

Dependencies
------------

causal-curve requires:

- black
- coverage
- future
- joblib
- numpy
- numpydoc
- pandas
- patsy
- progressbar2
- pygam
- pytest
- python-dateutil
- python-utils
- pytz
- scikit-learn
- scipy
- six
- sphinx_rtd_theme
- statsmodels



User installation
-----------------

If you already have a working installation of numpy, pandas, pygam, scipy, and statsmodels,
you can easily install causal-curve using ``pip``::

    pip install causal-curve


You can also get the latest version of causal-curve by cloning the repository::

    git clone https://github.com/ronikobrosly/causal-curve.git
    cd causal-curve
    pip install .


Testing
-------

After installation, you can launch the test suite from outside the source
directory using ``pytest``::

    pytest


Development
-----------

Please reach out if you are interested in adding additional tools,
or have ideas on how to improve the package!
