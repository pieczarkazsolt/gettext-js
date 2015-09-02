# Usage #

## HTML ##

```
<head>
    <link rel="gettext" lang="de" href="locale/de_test.po" />
</head>
```

## Javascript ##

```

Gettext.lang = 'de';
alert(_('The world is full of married men, %d','5'));

// or with a tuple-like second argument:
alert(_('%d hour, %d minutes and %d seconds',[hour, min, sec]));

```