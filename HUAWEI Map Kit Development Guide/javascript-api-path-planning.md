# Procedure<a name="EN-US_TOPIC_0000001145723505"></a>

1.  Initialize the  [HWDirectionsService](en-us_topic_0000001098683696.md)  object through  **HWMapJsSDK**.
2.  Construct the route planning request. You must pass the longitudes and latitudes of both the departure place and destination to the request.
    -   **origin**: longitude and latitude of the departure place.
    -   **destination**: longitude and latitude of the destination.

3.  Call the route planning API \(for example, the  **routeDriving**  API\) through the initialized  [HWDirectionsService](en-us_topic_0000001098683696.md)  object, and pass the created request and callback function to the API. 
4.  Define the callback function  **function\([DirectionsResult](en-us_topic_0000001098683696.md#s3d0982d140604e3099f8c3215ad8247c), DirectionsStatus\)**  for route planning. In the function,  [DirectionsResult](en-us_topic_0000001098683696.md#s3d0982d140604e3099f8c3215ad8247c)  indicates the route planning result and  **DirectionsStatus**  indicates the result code. If the result code is  **0**, the route planning is successful. 
5.  Render the route planning result. You can render the route planning result through multiple ways, for example, using the polyline drawing function or using the  [HWDirectionsRenderer](en-us_topic_0000001098683704.md)**.setDirections\([DirectionsResult](en-us_topic_0000001098683696.md#s3d0982d140604e3099f8c3215ad8247c)\)**  method. 

