# scary-cookie-consent

[![Build Status](https://travis-ci.org/Scarygami/scary-cookie-consent.svg?branch=master)](https://travis-ci.org/Scarygami/scary-cookie-consent)

Element to make it easier for you to display those annoying cookie message
you need to have when hosting a website in the EU.

You define your custom cookie message as content of the `scary-cookie-consent` element.

The message will contain a confirm and deny button. If you provide a `policy` link, an extra button will link to it.

You can position/size the cookie message via CSS:

```
scary-cookie-consent {
  position: fixed;
  bottom: 0;
  left: 0;
  right: 0;
}
```

You can style the look of the `scary-cookie-consent` toolbar using the
`--cookie-consent-toolbar` CSS mixin or the `--cookie-consent-background`
and `--cookie-consent-color` custom properties

```
scary-cookie-consent {
  --cookie-consent-toolbar: {
    color: white;
    background-color: black;
  };
}
```

```
scary-cookie-consent {
  --cookie-consent-color: white;
  --cookie-consent-background: black;
}
```
