This started as a fork of the light version of the Californium (Cf) CoAP framework called Cal-Lite. Ark-lite is a lightweight prototyping sandbox for a future full-featured Android CoAP framework named Ark. 

Ark-lite is designed to be built with Gradle and is currently Android specific, targeting Android 5.0+ (Lollipop). For compatibility reasons with other projects a backport to Android 4.2 (API 17) is planned to be maintained on a separate branch.

Things that have been removed from Californium:

* Any maven dependency
* Any plugin support

Things that have been removed from Cal-Lite:

* Any NetBeans dependency

Things that have been added:

* Gradle build support

Things that are planned:

* Re-organizing to make use of Android services
* Support for scripting CoAP resources via Bright, a Lua-based language developed by the USB pioneers at Moore Computer Consultants, Inc. (MCCI).




Visit https://github.com/nikosft/CoAP-examples for a list of examples on how to use it
