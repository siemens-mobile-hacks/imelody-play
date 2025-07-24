# imelody-play

This library can play simple melodies in iMelody format using Web Audio API.
iMelody format was used when sending messages via SMS.

## Installation
```sh
npm add imelody-play
```
## Example use

```js
import {playIMelody} from "./node_modules/imelody-play/imelody.js";
playIMelody(`BEGIN:IMELODY
VERSION:1.2
FORMAT:CLASS1.0
BEAT:80
MELODY:c3c4;d2;c2;f2;e1;c3c4;d2;c2;g2;f1;c3c4;*5c2;a2;
END:IMELODY`
);
```
Note: browsers require a user interaction to play sound, in practice, you'll want to bind this to a click or a similar event.

See index.html for an example of a click event.
Run `npx serve .` to run the example locally.
