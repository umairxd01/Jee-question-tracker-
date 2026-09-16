JEE Question Tracker — PWA manifest fix

Replace ONLY the existing manifest.webmanifest in the GitHub Pages repository with the manifest.webmanifest in this ZIP.

Do not replace index.html, sw.js, or the icons for this fix.

The manifest intentionally removes optional display_override/id/extra metadata so Chrome Android can generate the WebAPK using the simplest supported manifest configuration.
