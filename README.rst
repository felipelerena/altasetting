altasetting
===========

A python library to handle settings.
it expects a Settings file and a Default settings file
if the key is not found in the settings the default will be taken


How to install
--------------

::

    pip install altasetting

How to use
----------

::

    from altasetting import Settings

    settings = Settings("settings.yaml", "defaults.yaml")

    print settings.units.elephant
    print settings.units.elephant.speed
    print settings.buildings.farm

