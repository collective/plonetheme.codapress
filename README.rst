Introduction
============

The ``plonetheme.codapress`` package uses the *theming & packaging* features
available in `plone.app.theming`_ to make the theme `codapress`_ easily
available in `Plone 4.1`_ or higher.

.. image:: https://raw.github.com/collective/plonetheme.codapress/master/plonetheme/codapress/static/preview.png

Installation
============

Buildout
--------

To install this with buildout:

* Add ``plonetheme.codapress`` to your ``plone.recipe.zope2instance`` section's ``eggs`` parameter::

    [instance]
    recipe = plone.recipe.zope2instance
    ...
    eggs =
        ...
        plonetheme.codapress

* Re-run buildout, e.g. with::

    $ ./bin/buildout

.. _`codapress`: http://www.freelayoutsworld.com/free-layouts/preview/587757924/
.. _`plone.app.theming`: http://pypi.python.org/pypi/plone.app.theming
.. _`Plone 4.1`: http://pypi.python.org/pypi/Plone/4.1rc2
