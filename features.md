# Features

This application consists of many features like SUPPORT, EMAIL and Tasks.

**1.Support:** 

Here User can interact with the admin and able to raise the tickets/issues .

**Mark as Solved:**

If the issue is fixed by the admin then you\(user\) can mark it as SOLVED.

**2. Emails:**

By using this we can communicate with the other staff and customers with in the organisation.

We can also use the Email Templates \(Already created content\)

**3. Task:**

Here we can assign the tasks to your organisation members.

**4. Pusher Notifications:**

We are Integrated the laravel notifications by using Pusher push notifications\( [https://pusher.com/docs/push\_notifications](https://pusher.com/docs/push_notifications) \).

Here we used JavaScript and PHP script for sending notifications.

We are used pusher when Cancel Subscription, Resume Subscription, Change and Extend Subscriptions by admin. You can find the Desktop notifications\(Alert\) in User account\(Organization\).

In our App you can find the Code for pusher from bellow files.

JavaScript `resources/views/layouts/pusherjs.blade.php`

PHP `app/Listeners/Subscription/CancelSubscriptionListener.php`

**5. Laravel Backup**

We used "laravel filesystem" to backup the files and Database. We can save the files into Local and Dropbox. Mention the file names in `config/backup.php` which you want Back Up. You can include and exclude the files here.

Run the below command for Back Up.

```text
php artisan backup:run
```

For clean/clearing the Back Up run the below command

```text
php artisan backup:clean
```

**6.Paypal** 

PayPal is the faster, safer way to make an online payment, receive money.

* Paypal used for creating Subscriptions.
* We have integrated paypal by using laravel-paypal \([https://github.com/srmklive/laravel-paypal](https://www.gitbook.com/book/lcrm/lcrm/edit#)\).
* By using this paypal we can create recurring payment profile and manage recurring payments profile status.
* By using this feature customers can pay the invoices.

**7.European Vat** 

It supports European VAT with Stripe and Paypal . Here we have used Laravel "[vat-calculator](https://github.com/mpociot/vat-calculator)" for calculating European Vat.

**8.Multi Language**

We have added multi language feature by using gTranslator. Refer this \([https://github.com/chaibialaa/gTranslator](https://github.com/chaibialaa/gTranslator)\). You can choose/change the language from settings of ADMIN section as well as USER section.You can choose different language for ADMIN and USER.

**Note:** If you choose any language in user section then same language will be applicable for CUSTOMER and STAFF also.

