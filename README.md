# WordPress Content _beta_

This is a forked copy of the official WordPress repository, with a few changes to make hosting with Docker more convenient. It’s a work in progress. 🚧

It’s meant to be used together with a separate [blueprint repository](https://github.com/jimthoburn/wordpress-blueprint), for setting up an environment for WordPress to run in.

In addition to the steps listed in the [README](https://github.com/jimthoburn/wordpress-blueprint/blob/main/README.md), you may want to copy the [wp-config-sample-render.php](https://github.com/jimthoburn/wordpress-content-example/blob/main/html/wp-config-sample-render.php) file to `wp-config.php` and update the [key section](https://github.com/jimthoburn/wordpress-content-example/blob/main/html/wp-config-sample-render.php#L64-L71).

You may also want to update to the latest release of WordPress. This repository is currently up to date with [WordPress 6](https://github.com/WordPress/WordPress/tree/eeeaeb98bcb33f475573e8e7afa934b0b30ce215).
