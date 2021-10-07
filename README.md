# enspyrco

#### tinyurls

Because tinyurls are not controled by us directly, we made our own.

See `firebase.json` for a set of redirects used where there is not support for rich text links (eg. Discord, Meetup, etc.)

To get a new short url, add an entry to `firebase.json` "redirects" list then deploy the change:

```sh
firebase deploy
```
