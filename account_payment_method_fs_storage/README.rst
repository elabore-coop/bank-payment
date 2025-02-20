=================================
Account Payment Method Fs Storage
=================================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:5fdd9e0544188c66534eb934f371df6bd2ba27262433ea3344b40682a91aa855
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fbank--payment-lightgray.png?logo=github
    :target: https://github.com/OCA/bank-payment/tree/16.0/account_payment_method_fs_storage
    :alt: OCA/bank-payment
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/bank-payment-16-0/bank-payment-16-0-account_payment_method_fs_storage
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/bank-payment&target_branch=16.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

This Odoo addon enhances the payment mode functionality by introducing the ability to designate a specific storage location. 
Users can now specify a storage destination within the payment method, 
facilitating the automatic transfer of generated files to the designated location upon completing a payment transaction. 

**Table of contents**

.. contents::
   :local:

Installation
============

This module depends on :

* account_payment_order
* fs_storage

This module is part of the OCA/bank-payment suite.

Configuration
=============

For setting the Storage:

#. Activate "Use On Payment Method" on storage (boolean on form of Storage)
#. Go to Invoicing/Accounting > Configuration > Payment Methods
#. You can specify your storage on the payment method

Usage
=====

This module sepcifically works for SEPA Payment.
When generating payment file on a payment order, the file will be pushed to a specific storage (set on the payment method).

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/bank-payment/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/bank-payment/issues/new?body=module:%20account_payment_method_fs_storage%0Aversion:%2016.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* ACSONE SA/NV

Contributors
~~~~~~~~~~~~

* François Honoré <francois.honore@acsone.eu>
* Zina Rasoamanana <zina.rasoamanana@acsone.eu>

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

This module is part of the `OCA/bank-payment <https://github.com/OCA/bank-payment/tree/16.0/account_payment_method_fs_storage>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
