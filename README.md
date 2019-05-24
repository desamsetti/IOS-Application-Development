# IOS-Application-Development
This is the NIU Campus Walk IOS Application which has been developed using Swift 4.
We have used the Maps Framework along with CoreMotion and other elements like PolyLine etc.
This can be used as a Personal assistant or a Campus Guide for students at Northern Illinois University to know more about the University.
There are two routes, a Short route which contains 10 campus buildings and a Long route which contains all 28 campus buildings of NIU. Both the routes let the user make changes to the list of buildings they want to visit. Also, selecting a building changes the View to a Detailed view of the building which describes some details about the building. Each detail view also contains a play, pause and stop button to let the user listen to the facts.
This contains 10 buildings for the short route and 28 buildings for the long route.
We have used a recursive function(Can use Dynamic Programming here to reduce the time complexity, also Greedy Algorithm) for getting the latitudes and longitudes from an API and then calling the function gives the directions. This creates polylines between different buildings. Several UI elements like TableViews, Switches, buttons, ImageViews etc. have been used in this project.

This application is built on XCode 9.4, Swift 4 and iOS 11. 



<img src="https://github.com/desamsetti/desamsetti.github.io/blob/master/img/Apple/NIUCampusWalkApplicationGif.gif?raw=true"
     alt="Northern Illinois University Campus Walk iOS Application"
     style="float: left; margin-right: 10px;" />

