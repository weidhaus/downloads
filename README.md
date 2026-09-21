# downloads

Release artifacts and update feeds for [parrot](https://github.com/El-Patronum/parrot)
and [quill](https://github.com/El-Patronum/quill).

This repository holds **no source code**. It exists because Sparkle needs the
update feed and the disk images reachable without a login, and both apps live
in private repositories.

| | |
|---|---|
| `parrot/appcast.xml` | update feed parrot checks |
| `quill/appcast.xml` | update feed quill checks |
| Releases | the signed, notarized `.dmg` files themselves |

Every disk image is signed with a Developer ID certificate and notarized by
Apple, and every appcast entry is signed with an EdDSA key so an update cannot
be substituted in transit.

## Installing

Download the latest `.dmg` from [Releases](../../releases), open it, and drag
the app to Applications. Both apps update themselves after that.
