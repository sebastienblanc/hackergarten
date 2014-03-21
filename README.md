hackergarten
============
# Agenda

* 10:00-10:30 : Welcome and coffee
* 10:30-11:30 : Introduction and demo of Cordova / Push Plugin 
* 11:30-12:30 : Choose idea and setting up the environments
* 12:30-13:30 : Lunch
* 13:30-18:00 : Hacking Time !

# Ideas

* Write a demo app for the [Cordova AeroGear Push Plugin](https://github.com/aerogear/aerogear-pushplugin-cordova) : There is basic example provided with the plugin but it would be nice if we had a more complete example (reference) app. It must stay lean and simple but it should cover all the possible use cases (receiving in background/foreground) and the layout should be mobile first (using Bootstrap / Topcoat / Whatever).

* Write a demo app that combines the [Cordova AeroGear Push Plugin](https://github.com/aerogear/aerogear-pushplugin-cordova) and the [Cordova AeroGear Geofencing PLugin](https://github.com/aerogear/aerogear-geo-cordova) : The Geofencing Plugin detects when an user enters a specific geofence, combining that with the Push plugin could result in a really cool show case. Imagine an app when where you friends is around your area you receive a notification or when you walk close to your favorite shop it send you products that are on sale .... This idea implies also the creation of a backend app and could be a good opportunity to discover the [Unified Push Java Client](https://github.com/aerogear/aerogear-unifiedpush-java-client).

* Write a Vert.x Mod that wraps the [Unified Push Java Client](https://github.com/aerogear/aerogear-unifiedpush-java-client) : The idea is to be able to integrate easily a Vertx app with the UnifiedPush Server. This mod could wrap the Java Library and use Vertx's Event Bus to stay language agnostic. 

* Write a demo app that shows AeroGear's [iOS OAuth2 adapter](https://github.com/aerogear/aerogear-ios/) working with [Keycloak](http://www.jboss.org/keycloak). More detailled instruction can be found in [AeroGearAndKeyCloak](AeroGearAndKeyCloak.md)

* Building a Java Based User Interface (Swing / Eclipse plugin / Griffon / JavaFX ) for the [AeroGear Simple Push Java Client](https://github.com/aerogear/aerogear-simplepush-java-client)

# Cordova's crash course

Installing the CLI : https://github.com/apache/cordova-cli/blob/master/README.md


Create a new app : 
```
cordova create hackengartenApp
cd hackengartenApp
cordova platform add android
```

Add Push Plugin : 
```
cordova plugin add https://github.com/aerogear/aerogear-pushplugin-cordova.git
```
Build and deploy : 
```
cordova build android
cordova run android
```

# Resources

* UnfifiedPush Instance for the Hackergarten : https://hackergartenups-sblanc.rhcloud.com
* http://aerogear.org/
* http://cordova.apache.org/
* https://www.openshift.com/






 
