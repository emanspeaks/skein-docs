# skein-docs

A mirror of the documentation site of [skein](https://github.com/chasingdaylight/skein), published with GitHub Pages under this repository's custom domain.

There is no content here. The workflow `.github/workflows/pages.yml` checks out skein, builds the site with skein's own script, and publishes it. To change the documentation, change it in skein.

It runs when skein publishes its own site: that workflow commits the hash of the commit it built to `source.txt` here, with a deploy key that can write to this repository alone, and the push starts the build. It also runs every day and by hand.
