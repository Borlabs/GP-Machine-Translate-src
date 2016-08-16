# GP Machine Translate
A machine translate plugin for [GlotPress as a WordPress plugin](https://github.com/GlotPress/GlotPress-WP).

Three machine translation providers are supported (though only one at a time):

* Google Translate (pay per character)
* Microsoft Translator (free tier available)
* translte.org (free)
* Yandex.Translate (free but requires Yandex account)

## Google

Login to your [Google developers console](http://console.developer.google.com) and select "APIs & auth"->Credentials.  Then create a new "Public API access" Key.  Use this key as below to configure access.

Once you have the Google API key, you can set the key for all users or a specific user.

## Microsoft Translator

Too be completed later.

## translte.org

Too be completed later.

## Yandex.Translate

Too be completed later.

[Powered by Yandex.Translate](http://translate.yandex.com/).

## Setting the API key once you have it

To set it for all users, go to the WordPress Dashboard, then Settings, then "GP Machine Translate" and set the API key.

To set if for a specific user, go to the users profile and scroll down to the "GP Machine Translate" section and set the API key.

Note, if both a global and user API key are set, the user API key will override the global API key.

