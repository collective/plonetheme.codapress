====================
plonetheme.codapress
====================


Introduction
============

*plonetheme.codapress* package is an installable Plone_ Theme using the **theming** and **packaging** 
features available in `plone.app.theming`_ to make `codapress`_ theme easly available in `Plone`.


Requirements
============

- From the Plone 4.1.x To the Plone 4.3 latest versión (https://plone.org/download)
- The ``plone.app.theming`` package (*will be installed as a dependency of this package*)


Screenshots
===========

Layout of the site when viewed in a computer resolution:

.. image:: https://raw.github.com/collective/plonetheme.codapress/master/plonetheme/codapress/static/preview.png


Features
========

- It's an installable Plone_ Theme package.
- After installation from Add-ons controlpanel, this theme is enabled automatically.
- Also it's a simple Diazo_ package (Zip file).
- It's have support for clean uninstallation.


Installation
============


Zipfile
-------

If you are an **end user**, you might enjoy installation via zip file import.

1. Download the `zip file <https://github.com/collective/plonetheme.codapress/raw/master/codapress.zip>`_.
2. Import the theme from the Diazo theme control panel.


Buildout
--------

If you are a **developer user**, you might enjoy installing it via buildout.

For install ``plonetheme.codapress`` package add it to your ``buildout`` section's 
*eggs* parameter e.g.: ::

   [buildout]
    ...
    eggs =
        ...
        plonetheme.codapress


and then running ``bin/buildout``.

Or, you can add it as a dependency on your own product ``setup.py`` file: ::

    install_requires=[
        ...
        'plonetheme.codapress',
    ],


Enabling the theme
^^^^^^^^^^^^^^^^^^

Browse to ``http://yoursite/Plone/@@theming-controlpanel`` click on ``Enable`` 
on ``Codapress`` theme from the Diazo control panel. That's it!


Contribute
==========

- Issue Tracker: https://github.com/collective/plonetheme.codapress/issues
- Source Code: https://github.com/collective/plonetheme.codapress


License
=======

This package is licensed under the GPL Version 2.


Credits
-------

- Giacomo Spettoli (giacomo.spettoli at gmail dot com).
- Leonardo J. Caballero G. (leonardocaballero at gmail dot com).

.. _`Plone`: http://plone.org
.. _`plone.app.theming`: https://pypi.org/project/plone.app.theming/
.. _`codapress`: http://www.freelayoutsworld.com/free-layouts/preview/587757924/
.. _`Diazo`: http://diazo.org
