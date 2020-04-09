# Paypal

PayPal is the faster, safer way to make an online payment, receive money. By using this feature customers can pay the invoices.

We have integrated paypal by using laravel-paypal \([https://github.com/srmklive/laravel-paypal](https://www.gitbook.com/book/lcrm/lcrm/edit#)\). For this you need to follow the below steps

* First you need to have an pay pal account or else create an account here \([https://www.paypal.com](https://www.paypal.com/)\)
* **For Live credentials**: We should have API credentials for those we credentials we need to create Paypal developers account\([https://developer.paypal.com/docs/classic/api/apiCredentials/\#create-an-api-signature](https://developer.paypal.com/docs/classic/api/apiCredentials/#create-an-api-signature)\)

**For Sandbox Credentials:**

* To create sandbox paypal account \([https://developer.paypal.com/docs/classic/lifecycle/sb\_create-accounts/](https://developer.paypal.com/docs/classic/lifecycle/sb_create-accounts/)\) please follow the steps which were provided in the link.
* After finishing the above step, you can see the accounts/emails which you have created \(Business and buyers\). Click on the Business account which displays **Profile** & **Notifications.**
* Click on the **Profile,**you can see a modal with different tabs.
* Choose the **API Credentials Tab**
* Here you can get the API Credentials. Use those credentials in the **LCRM Settings Page**

Note:

Don't get confuse between **PAYPAL\_SANDBOX\_API\_SECRET** and **Signature**. Both are same.

**Handling Paypal IPN:**

You can also handle Instant Payment Notifications from PayPal. Suppose you have set IPN URL to [http://saas-demo.lcrmapp.com/ipn/notify/](http://saas-demo.lcrmapp.com/ipn/notify/) in PayPal.

* To handle Paypal IPN refer laravel paypal documentation [https://github.com/srmklive/laravel-paypal\#paypalipn](https://github.com/srmklive/laravel-paypal#paypalipn)

**Setting up IPN Notifications on paypal:**

To setup the ipn notifications refer the paypal documentation [https://developer.paypal.com/docs/classic/ipn/integration-guide/IPNSetup/](https://developer.paypal.com/docs/classic/ipn/integration-guide/IPNSetup/)

