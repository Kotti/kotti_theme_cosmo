==================
kotti_theme_cosmo
==================

Cosmo theme from http://bootswatch.com/cosmo/ for Kotti.

`Find out more about Kotti`_

Setup
=====

To activate the ``kotti_theme_cosmo`` theme in your Kotti site, you need to
add an entry to the ``kotti.configurators`` setting in your Paste
Deploy config.  If you don't have a ``kotti.configurators`` option,
add one.  The line in your ``[app:main]`` (or ``[app:kotti]``, depending on how
you setup Fanstatic) section could then look like this::

    kotti.configurators = kotti_theme_cosmo.kotti_configure


.. _Find out more about Kotti: http://pypi.python.org/pypi/Kotti