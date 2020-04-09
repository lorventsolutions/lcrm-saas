# Laravel Vat

Handle all the hard stuff related to EU MOSS tax/vat regulations, the way it should be. Can be used with **Laravel 5 / Cashier**— or **standalone**.

For more detail understanding refer this [https://github.com/mpociot/vat-calculator](https://github.com/mpociot/vat-calculator)

**Vat for User:**

Vat is applied to the users when admin has European Vat **TRUE** in settings . Vat is applied based on the IP address\(location\).

Ex: Vat of the "User" is calculated based on the "Admin" location. If admin is in Netherlands then all the users should pay the tax of 21% while subscribing to the plan.

**Note:** If user has a VAT NUMBER then no need to pay the VAT. User should mention the valid VAT NUMBER in user settings.

**Vat for Customer:**

Vat is applied to the Customer when User has European Vat **TRUE** in settings . Vat is applied based on the IP address\(location\) .

Ex: Vat of the "Customer" is calculated based on the "User" location. If admin is in Netherlands then all the Customers should pay the tax of 21% while paying the invoices.

**Note:** If Customer has a VAT NUMBER then no need to pay the VAT. Customer should mention the valid VAT NUMBER in Customer settings\(If Customers belong to same company then they will be having same VAT Number\).

1. If customer has vat number, in invoice page he able to see the total amount \(including vat\) but while paying the invoice he can see the deducted amount\(removal of vat amount\) 

**Important note:** 

Lcrm Saas does not guarantee 100% compliance with EU VAT regulations. We gave it our best and will accept improvements if any.

