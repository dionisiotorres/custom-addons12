![Odoo Logo](/setup/odoo_logo.png)
# Odoo Custom Addons

[![Build Status](https://travis-ci.org/LuqueDaniel/odoo-custom-addons.svg?branch=10.0)](https://travis-ci.org/LuqueDaniel/odoo-custom-addons)

This repository contains addons that extend / modify parts of
**[Odoo](https://www.odoo.com/)** ERP.

## Addons list

* [account_cancel_permission](https://github.com/LuqueDaniel/odoo-custom-addons/tree/10.0/account_cancel_permission)
  (10.0.1.0.0)
    * Only shows the button to cancel invoices, payments and bank statements to
      users with **Cancel Journal Entries** permission.
* [account_invoice_financial_risk_filter](https://github.com/LuqueDaniel/odoo-custom-addons/tree/10.0/account_invoice_financial_risk_filter)
  (10.0.1.0.1)
    * Adds the ability to filter invoices through the customer's policy field.
* [account_invoice_payment_partner_required](https://github.com/LuqueDaniel/odoo-custom-addons/tree/10.0/account_invoice_payment_partner_required)
  (10.0.1.0.0)
    * Makes the Payment Mode and Payment Terms fields of the invoice mandatory.
* [account_payment_partner_required](https://github.com/LuqueDaniel/odoo-custom-addons/tree/10.0/account_payment_partner_required)
  (10.0.1.0.0)
    * Makes the Partner Payment Mode and Partner Payment Terms fields mandatory.
* [account_vendor_reference_required](https://github.com/LuqueDaniel/odoo-custom-addons/tree/10.0/account_vendor_reference_required)
  (10.0.1.0.0)
    * Makes the Vendor Reference field mandatory.
* [hide_cost_margin](https://github.com/LuqueDaniel/odoo-custom-addons/tree/10.0/hide_cost_margin)
  (10.0.1.0.1)
    * Hides the cost and margin prices for all users who don't have the
      `Show costs and margins` permission.
* [partner_tag_append_model](https://github.com/LuqueDaniel/odoo-custom-addons/tree/10.0/partner_tag_append_model)
  (10.0.1.0.0)
    * Adds partner tag field to invoices and sale orders.
* [pos_margin_report](https://github.com/LuqueDaniel/odoo-custom-addons/tree/10.0/pos_margin_report)
  (10.0.1.0.1)
    * Sales margins in PoS orders analysis report.
* [stock_location_fields_char](https://github.com/LuqueDaniel/odoo-custom-addons/tree/10.0/stock_location_fields_char)
  (10.0.1.0.0)
    * This addon replaces the `int` fields of the `stock.location` model with
      new ones of type `char`.
* [vat_checker](https://github.com/LuqueDaniel/odoo-custom-addons/tree/10.0/vat_checker)
  (10.0.1.0.0)
    * Check if the customer has a VAT before creating an invoice from a sale
      order.

## License

[**AGPL-3.0**](http://www.gnu.org/licenses/agpl)

## Thanks to

- **OCA** Odoo Community Association (https://github.com/OCA)
