==================================
Stock Location Product Restriction
==================================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:084f1ba2706bd03f357d31d4e11b08d07211f78f38647e4ddd7f8827f5e8a7fb
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fstock--logistics--warehouse-lightgray.png?logo=github
    :target: https://github.com/OCA/stock-logistics-warehouse/tree/16.0/stock_location_product_restriction
    :alt: OCA/stock-logistics-warehouse
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/stock-logistics-warehouse-16-0/stock-logistics-warehouse-16-0-stock_location_product_restriction
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/stock-logistics-warehouse&target_branch=16.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

This module extends the functionality of stock to allow you to prevent to put
items of different products into the same stock location.

**Table of contents**

.. contents::
   :local:

Usage
=====

By default, Odoo allows you to put items of any product into the same location.
This behaviour remains the one by default once the addon is installed.
Once installed, you can specify at any level of the stock location hierarchy
if you want to restrict the usage of the location to only items of the same
product. This property is inherited by all the children locations while you
don't specify an other specific value on a child location. The constrains only
applies location by location.

Once a location is configured to only contains items of the same product, the
system will prevent you to move items of any others products into a location
that already contains product items. A new filter into the tree view of the
stock locations will also allow you to find all the location where this new
restriction is violated.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/stock-logistics-warehouse/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/stock-logistics-warehouse/issues/new?body=module:%20stock_location_product_restriction%0Aversion:%2016.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* ACSONE SA/NV

Contributors
~~~~~~~~~~~~

* Laurent Mignon <laurent.mignon@acsone.eu> (https://www.acsone.eu/)
* Denis Roussel <denis.roussel@acsone.eu> (https://www.acsone.eu/)

Other credits
~~~~~~~~~~~~~

The development of this module has been financially supported by:

* ACSONE SA/NV
* Alcyon Benelux

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

.. |maintainer-lmignon| image:: https://github.com/lmignon.png?size=40px
    :target: https://github.com/lmignon
    :alt: lmignon
.. |maintainer-rousseldenis| image:: https://github.com/rousseldenis.png?size=40px
    :target: https://github.com/rousseldenis
    :alt: rousseldenis

Current `maintainers <https://odoo-community.org/page/maintainer-role>`__:

|maintainer-lmignon| |maintainer-rousseldenis| 

This module is part of the `OCA/stock-logistics-warehouse <https://github.com/OCA/stock-logistics-warehouse/tree/16.0/stock_location_product_restriction>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
