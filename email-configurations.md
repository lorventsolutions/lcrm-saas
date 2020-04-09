# Email Configuration

We can send the mails using SMTP, SES and Mailgun drivers. In SMTP we can use Mailtrap, Gmail and Elastic Email for sending mails. Refer the laravel mail documentation [https://laravel.com/docs/5.5/mail](https://laravel.com/docs/5.5/mail) for better understanding.

**Mailtrap Configuration:**

MAIL\_DRIVER=smtp

MAIL\_HOST=**smtp.mailtrap.io**

MAIL\_PORT=25 or 465 or 2525

MAIL\_USERNAME=username

MAIL\_PASSWORD=password

MAIL\_ENCRYPTION=ssl

**Gmail Configuration:**

MAIL\_DRIVER=smtp

MAIL\_HOST=**smtp.gmail.com**

MAIL\_PORT=465

MAIL\_USERNAME=emailid

MAIL\_PASSWORD=password

MAIL\_ENCRYPTION=ssl

**Elastic Email:**

MAIL\_DRIVER=smtp

MAIL\_HOST=**smtp.elasticemail.com**

MAIL\_PORT=2525

MAIL\_USERNAME=username

MAIL\_PASSWORD=password

MAIL\_ENCRYPTION=tls

**Amazon SES:**

MAIL\_DRIVER=ses

SES Key=

SES Secret=

SES Region=

Refer the documentation for getting the credentials and activating your account [https://docs.aws.amazon.com/ses/latest/DeveloperGuide/Welcome.html](https://docs.aws.amazon.com/ses/latest/DeveloperGuide/Welcome.html)

For better understanding of AWS Regions and End points the link [https://docs.aws.amazon.com/general/latest/gr/rande.html](https://docs.aws.amazon.com/general/latest/gr/rande.html)

**Note:** Before sending email through amazon ses you should verify sender and receiver email addresses.

**Mailgun Driver:**

MAIL\_DRIVER=mailgun

MAILGUN\_DOMAIN=

MAILGUN\_SECRET=

MAIL\_ENCRYPTION=tls

**Note:** Before sending email through Mailgun driver you should verify receiver email address.

**Note:** We have overrided all these credentials in "app/Providers/AppServiceProvider.php"

