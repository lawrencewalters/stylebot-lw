Stylebot LW
===============

I wanted to get a custom, transparent logo in my company's google apps view.... this is how I did it. Added a single image, and then reference it in a stylebot rule.

```
img.gb_0b {
    height: 0px;
    padding: 60px 144px 0px 0px;
    width: 0px;
}

span.gb_0a.gb_Za {
    background-image: url('chrome-extension://oiaejidbmkiecgbjeifoejpgmdaleoha/images/lyonscglogotransparent.png');
}
```

copied from chrome webstore. original content at: https://github.com/ankit/stylebot