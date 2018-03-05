[![Latest Version](https://img.shields.io/pypi/v/cmsplugin_instagram.svg)](https://pypi.python.org/pypi/cmsplugin-instagram/)
[![Supported Python versions](https://img.shields.io/pypi/pyversions/cmsplugin_instagram.svg)](https://pypi.python.org/pypi/cmsplugin-instagram/)
[![Development Status](https://img.shields.io/pypi/status/cmsplugin_instagram.svg)](https://pypi.python.org/pypi/cmsplugin_instagram/)
[![Code Climate](https://codeclimate.com/github/creimers/cmsplugin_instagram/badges/gpa.svg)](https://codeclimate.com/github/creimers/cmsplugin_instagram)
# djangocms instagram plugin

This plugin displays pictures from an instagram account on a djangocms site.

## Installation

* ``pip install cmsplugin_instagram``

* add ``cmsplugin_instagram`` to ``INSTALLED_APPS`` in ``settings.py``

if you're using Django >= 1.7:

* add ``'cmsplugin_instagram': 'cmsplugin_instagram.migrations_django'`` to ``MIGRATION_MODULES`` in ``settings.py``

* migrate the database
