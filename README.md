# Clima Location Refactoring Challenge

* Refactor the Clima app's code so that all the logic of getting the current location will be handled by a dedicated ```Location``` object. 

* Creating a seperate ```Location``` class in the location.dart file. 

* This class needs to have two properties: a ```latitude``` and a ```longitude```. 

* The ```Location``` class also needs to have a method called ```getCurrentLocation()```. Move the try-catch block with the code where you ```getCurrentPosition()``` in the loading_screen to the ```getCurrentLocation()``` method. 

* In the loading_screen.dart update ```getLocation()``` so that you 1) create a new ```Location``` object, 2) you call the ```getCurrentLocation()``` method, and 3) you print the values stored inside ```latitude``` and ```longitude```. 
