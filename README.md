Download Link: https://assignmentchef.com/product/solved-itis-cs-5180-assignment9-google-maps
<br>
In this assignment you will interface Google Maps into your app, and include poly lines and markers in the app.

<strong><u>Part 1: </u></strong>

<ol>

 <li>Create an activity and include Google maps in this activity. Follow all the instructions indicated in the Google Maps documentation.</li>

</ol>

<strong><u>Part 2: </u></strong>

<ol>

 <li>You are provided with a “trip.json” file, which should be added to your project as follows:

  <ol>

   <li>Create a “raw” folder under the “res” folder.</li>

   <li>Copy the “trip.json” file into the “raw” folder.</li>

  </ol></li>

 <li>After the Map is loaded into the activity, your code should read and parse the “trip.json” file, (you can use the Gson library to parse the json file).</li>

 <li>The trip points loaded from the “trip.json” file should be plotted on the Google map as follows:

  <ol>

   <li>The trip should be displayed using the “Polyline” shape.</li>

   <li>The start and end points of the trip should be indicated with markers</li>

  </ol></li>

 <li>After plotting the trip information the map should be centered and zoomed to display all the trip points. Also map should be auto zoomed to include all the trip points in the map’s bounding box. Check CameraUpdateFactory class at the following link
 <a href="https://developers.google.com/android/reference/com/google/android/gms/maps/CameraUpdateFactory">https://developers.google.com/android/reference/com/google/android/gms/maps/CameraUpdateFactory</a></li>

</ol>

<strong>Figure 1, App Wireframe</strong>