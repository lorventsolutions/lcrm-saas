# Prerequisite

You need to fulfil the following requirements before installing Lcrm Saas.

**Server Requirements:**

Lcrm Saas is based on [Laravel](https://laravel.com) framework. Laravel have a few [requirements](https://laravel.com/docs/5.5#server-requirements) of its own. Make sure that your server satisfies these requirements.

Also make sure that you [configure](https://laravel.com/docs/5.5#web-server-configuration) your web-server.

**Note:** Because of a Dependency you need to use **php 7.1** or above

**Database details:**

Before installing make sure you have created a database and have the necessary connection details.

You need to enter them during the installation process.

**Activated Stripe Account :** 

Lcrm saas uses [stripe](https://stripe.com/) to accept payments and implement subscriptions. In order to receive the payments you should have an [activated stripe account](https://stripe.com/docs/dashboard#activating-your-account).

**Stripe Webhook:**

When using stripe if something happens on stripe's end, we will be informed through [webhooks](https://stripe.com/docs/webhooks).

Eg: Failing to charge the users card

In order to receive the events from stripe we need to setup a webhook in the stripe [dashboard](https://dashboard.stripe.com/account/webhooks).

For this project you need to set the webhook to pointing to `stripe/webhook`.

**Eg:** If your URL is `saas.com`then the webhook URL in the stripe should be `saas.com/stripe/webhook`

**SMTP Details :**

In order to send mails you need to enter the smtp details.

Make sure you have them, or else no mails will be sent and the users won't be notified of certain events from the app.

