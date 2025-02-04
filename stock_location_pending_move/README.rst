===========================
Stock Location Pending Move
===========================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:1270f758e555a1c035326ce5bca4caeda58d0bdc7b0609176f812326a3c235b4
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fstock--logistics--warehouse-lightgray.png?logo=github
    :target: https://github.com/OCA/stock-logistics-warehouse/tree/16.0/stock_location_pending_move
    :alt: OCA/stock-logistics-warehouse
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/stock-logistics-warehouse-16-0/stock-logistics-warehouse-16-0-stock_location_pending_move
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/stock-logistics-warehouse&target_branch=16.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

This module allows to access incoming and ougoing pending moves from a
stock location.

- Stock Location view:

|Pending Moves|

- Detail grouped per origin location:

|Detailed view|

.. |Pending Moves| image:: https://raw.githubusercontent.com/OCA/stock-logistics-warehouse/16.0/stock_location_pending_move/static/description/pending_moves.png
.. |Detailed view| image:: https://raw.githubusercontent.com/OCA/stock-logistics-warehouse/16.0/stock_location_pending_move/static/description/pending_moves_detail.png

**Table of contents**

.. contents::
   :local:

Use Cases / Context
===================

When user wants to make a diagnostic on a particular stock location, it
is useful to have pending stock moves that will go in or go out (you can
also go to 'Moves History' but you need to use a filter on stock
location).

Configuration
=============

[ This file is not always required; it should explain **how to configure
the module before using it**; it is aimed at users with administration
privileges.

Please be detailed on the path to configuration (eg: do you need to
activate developer mode?), describe step by step configurations and the
use of screenshots is strongly recommended.]

To configure this module, you need to:

- Go to *App* > Menu > Menu item
- Activate boolean… > save
- …

Usage
=====

- Storage Locations should have been enabled.
- Go to Inventory > Configuration > Warehouse Management > Locations
- Click on 'Pending Move' to see stock moves.
- Click on 'Pending Operations' to see detailed operations.
- By default, the moves are displayed grouped by source location in
  order to easy review if there are plenty of moves.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/stock-logistics-warehouse/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/stock-logistics-warehouse/issues/new?body=module:%20stock_location_pending_move%0Aversion:%2016.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
-------

* ACSONE SA/NV
* BCIM
* Camptocamp

Contributors
------------

- Denis Roussel denis.roussel@acsone.eu
- Guewen Baconnier
- Akim Juillerat akim.juillerat@camptocamp.com
- Alexandre Fayolle alexandre.faoylle@camptocamp.com

Maintainers
-----------

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

.. |maintainer-rousseldenis| image:: https://github.com/rousseldenis.png?size=40px
    :target: https://github.com/rousseldenis
    :alt: rousseldenis
.. |maintainer-jbaudoux| image:: https://github.com/jbaudoux.png?size=40px
    :target: https://github.com/jbaudoux
    :alt: jbaudoux

Current `maintainers <https://odoo-community.org/page/maintainer-role>`__:

|maintainer-rousseldenis| |maintainer-jbaudoux| 

This module is part of the `OCA/stock-logistics-warehouse <https://github.com/OCA/stock-logistics-warehouse/tree/16.0/stock_location_pending_move>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
