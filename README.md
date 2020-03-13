heroku-buildpack-imagick
=================================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for vendoring the PHP Extension Imagick into your project

Set the version of ImageMagick using the IMAGE_MAGICK_VERSION env var in your environment.
Set the version of Imagick using the IMAGICK_VERSION env var in your environment.

Run locally:
```sudo STACK=heroku-18 bin/compile /tmp/build /tmp/cache```