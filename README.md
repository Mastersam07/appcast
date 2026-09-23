# appcast

Sparkle update feeds for my apps, served through GitHub Pages.

Each app has one feed at a permanent URL:

| App | Feed |
|---|---|
| OpenDeviceHub | https://mastersam07.github.io/appcast/simviewer.xml |

A feed URL is baked into a released app and can never change: changing it silently ends updates
for everyone who already installed that app. The feeds live here rather than in an app's own
repository so the app repository can be renamed freely. The `<enclosure>` URLs inside a feed point
at that app's release downloads and are rewritten on every release.
