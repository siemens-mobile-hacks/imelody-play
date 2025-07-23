# imelody-play

This library can play simple melodies in iMelody format.
iMelody format was used when sending messages via SMS.

## Example use
```js
playIMelody(`BEGIN:IMELODY
VERSION:1.2
FORMAT:CLASS1.0
BEAT:80
MELODY:c3c4;d2;c2;f2;e1;c3c4;d2;c2;g2;f1;c3c4;*5c2;a2;
END:IMELODY`
);
```

See index.html for an example of how to include the library on the page.

Run `npx serve .` to run the example locally.
