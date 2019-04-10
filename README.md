# Clima Location Refactoring Challenge

Refactor the Clima app's code so that all the logic of getting the current location will be handled by a dedicated '''Location''' object. 

This means creating a seperate Location() class in the location.dart file. 

This class needs to have two properties: a latitude and a longitude. 

It also needs to have a method called getCurrentLocation(). This is where you'll need to move the try-catch block from the loading_screen. 

Back in the loading_screen update the getLocation() method so that you create a new location object, you call the getCurrentLocation() method, and then you print the latitude and the longitude that were stored in 

