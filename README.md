facebook-webapp
===============

This is a demo of how the Facebook JS SDK is broken when you have added the meta tag

```
<meta name="apple-mobile-web-app-capable" content="yes" />
```

and you use the iOS add to homescreen option.

This places your webapp on their homescreen in chromeless mode.

This means you can't open popup windows and the FB SDK fails to return to your webapp on login.


You can see this running at http://webapp.netproteus.com

All this app should do when you click on login is request Facebook login with a few permissions and then throw up an alert dialogue with the resulting access token.

