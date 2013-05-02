facebook-webapp
===============

This is a demo of how the Facebook JS SDK is broken when you have added the meta tag

```html
<meta name="apple-mobile-web-app-capable" content="yes" />
```

and you use the iOS add to homescreen option.

This places your webapp on their homescreen in chromeless mode.

This means you can't open popup windows and the FB SDK fails to return to your webapp on login.
