.. image:: https://img.shields.io/badge/license-AGPLv3-blue.svg
   :target: https://www.gnu.org/licenses/agpl.html
   :alt: License: AGPL-3

==========================
Account Move Line RMA Line
==========================

This module will add the RMA order line to journal items.

The ultimate goal is to establish the RMA order line as one of the key
fields to reconcile the Goods Received Not Invoiced accrual account.


Usage
=====

The RMA order line will be automatically copied to the journal items.

* When a supplier invoice is created referencing RMA orders, the
  RMA order line will be copied to the corresponding journal item.

* When a stock move is validated and generates a journal entry, the RMA
  order line is copied to the account move line.

.. image:: https://odoo-community.org/website/image/ir.attachment/5784_f2813bd/datas
   :alt: Try me on Runbot
   :target: https://runbot.odoo-community.org/runbot/92/9.0

Bug Tracker
===========

Bugs are tracked on `GitHub Issues
<https://github.com/Eficent/stock_rma/issues>`_. In case of trouble, please
check there if your issue has already been reported. If you spotted it first,
help us smashing it by providing a detailed and welcomed feedback.


Credits
=======

Images
------

* Odoo Community Association: `Icon <https://github.com/OCA/maintainer-tools/blob/master/template/module/static/description/icon.svg>`_.

Contributors
------------

* Jordi Ballester Alomar <jordi.ballester@eficent.com>
* Aarón Henríquez Quintana <ahenriquez@eficent.com>

Maintainer
----------

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

This module is maintained by the OCA.

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

To contribute to this module, please visit https://odoo-community.org.
