Google-Glass-Launch-Custom-App
==============================

A way to Launch a custom app using the default voice commands

ManifestGlassCamera.xml is the manifest file of the glassCamera app that comes in Google Glass.
So here I have developed a normal app and renamed the package name to the package name to the GlassCamera'a package
name and replaced the intent filter of my app with the glass camera Activity's intent filter.

Before installing the modified app dont forget to backup the glasscamera app and delete it, if not the OS will not allow
our modified app to be installed as both have the same package name

So now when you say ok glass take a picture instead of firing the default glassCamera app the glass will launch my app.

Enjoy
