# 180
The %2C in the URL represents the comma and %3B represents the semi-colon. This special encoding is done for the URLs to transfer data

We can set the type of the API call as ‘get’ to get the directions in the response.


he success callback of an AJAX request takes an argument response which contains the response from the API. Let’s add it and see what it gives us.

Recap:

● We created a Mapbox account and learned to render maps using Mapbox JS GL library.
● We used the Map object to render maps using the user’s Mapbox account access token.
● We learned to add controls (using Map object methods) to the maps like MapboxDirections and GeolocateControl.
● Finally we created two web pages and used query parameters to get the longitude and latitude coordinates of the source and destination from the
URL of the main web page on the next page
----------------------------------------------------------------
tODAY'S CLASS IS location based augmented reality, then we will merge all concepts Together to create augmented reality navigation.

We have used different types of markers to render augmented objects in the scene and we can use our location instead of markers to create markerless augmented scenes

We will continue using A-Frame to create location based augmented reality
--------------------------------------------------------------------------------

we will need A-Frame and AR.js libraries.

To initialize arjs in the scene ,We can attach the arjs component in the <scene>
 
we can render 3D models, images, videos, text or any other assets in AR
  
We have a 3D model of a ball that we can use.

  
  We can use the
<a-assets> tag, then to add
3D models we will use
<a-asset-item>
  
  we can use the <a-entity> tag
to add the 3D model in the scene.
We can set the rotation, position and
scale attributes to set the orientation
and size of the mode
