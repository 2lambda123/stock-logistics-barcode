=====================
Stock Scanner Receipt
=====================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:9270364ee3fb048a5d5439c96ea838e50b61a8066a8e555d803b3b7932ca3f31
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fstock--logistics--barcode-lightgray.png?logo=github
    :target: https://github.com/OCA/stock-logistics-barcode/tree/10.0/stock_scanner_receipt
    :alt: OCA/stock-logistics-barcode
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/stock-logistics-barcode-10-0/stock-logistics-barcode-10-0-stock_scanner_receipt
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/stock-logistics-barcode&target_branch=10.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

This module installs a scenario which allows the user to process an incoming picking.

The scenario starts by calling the "Picking name input" step, then goes to a loop containing these four steps :

* Product name input
* Quantity input
* Lot name input (if applicable)
* Location name input

When the user enters an empty value for the product's name, this ends the loop, and goes to the "End confirm" step.

If the user confirms, the picking is validated, otherwise, the scenario returns to the product name input step.

.. image:: https://raw.githubusercontent.com/OCA/stock-logistics-barcode/10.0/stock_scanner_receipt/images/scenario.png

**Table of contents**

.. contents::
   :local:

Installation
============

Just install the module from Odoo.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/stock-logistics-barcode/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/stock-logistics-barcode/issues/new?body=module:%20stock_scanner_receipt%0Aversion:%2010.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* SYLEAM

Contributors
~~~~~~~~~~~~

* Sylvain Garancher <sylvain.garancher@syleam.fr>

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

This module is part of the `OCA/stock-logistics-barcode <https://github.com/OCA/stock-logistics-barcode/tree/10.0/stock_scanner_receipt>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
