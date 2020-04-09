# Multi Language

We have added multi language feature by using gTranslator. Refer this \([https://github.com/chaibialaa/gTranslator](https://github.com/chaibialaa/gTranslator)\). You can choose/change the language from settings of ADMIN section as well as USER section.You can choose different language for ADMIN and USER.

**Note:** If you choose any language in user section then same language will be applicable for CUSTOMER and STAFF also.

**Translate the Language:**

If you want to add new language run "**php artisan translate**" in terminal then you can see

From which language ? \[en\]: en \(type "en" then hit enter\)

\(mention the language code from which language you want to change \)

After that you can see

To which language ? \[en\]:es

\(mention the language code to which language you want to convert\)

**Add new language in settings:**

If you want to get the new language in settings\(language\) you need to save the new language in "**options**" table. Create the new seeder like "**database/seeds/LanguageSeeder.php**" with your new language. Then run "**php artisan db:seed --class=SeederName**" then you can get the languages into setting whatever you want.

