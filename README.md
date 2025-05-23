# The Reach Fast app is designed to help users find the most efficient route between multiple areas and calculate the total gas cost for the trip. It provides users with a way to input locations,
calculates the shortest path between them, and determines the cost of fuel required based on the total distance.

![Gas app images](https://github.com/user-attachments/assets/08a7841f-bc88-472c-878e-1afa92028bc8)

![ezgif-7-7ca2f3c10f](https://github.com/user-attachments/assets/c0bebc71-0711-4d6f-ae21-2116c92efeb2)

# Features->
-Best Route Calculation: Finds the shortest route between multiple areas using permutations and calculates the total distance.

-Gas Cost Estimation: Calculates the gas cost for the trip based on the distance and a standard fuel efficiency rate.

-Location Tracking: Integrates AirLocation to detect the user's current location.

-Area History: Allows users to input and save areas, and the app maintains a history of previous calculations, which is reset every 48 hours.

-Persistent Storage: Stores user inputs, results, and history using SharedPreferences, ensuring that the data is saved between app sessions.

-RecyclerView for Display: Displays the list of areas and history using RecyclerView for a smooth user experience.

# What I Learned from Building This App->
-AirLocation Library: I learned how to use the AirLocation library to get accurate GPS coordinates for a user’s current location and handle the success or failure of location requests.
This enhanced my understanding of integrating third-party libraries and handling asynchronous operations.

-Geocoder API: Using Geocoder to convert location names into coordinates was insightful. It deepened my knowledge of working with location-based services in Android and handling address-to-coordinate conversions for route calculations.

-SharedPreferences: I learned how to save and retrieve data persistently using SharedPreferences. This was particularly helpful for storing user data (like areas and results) between sessions.
It also taught me how to implement automatic history resetting after a set period (48 hours in this case).

-RecyclerView and Adapters: I expanded my skills in creating dynamic lists using RecyclerView with custom adapters. I used it to display areas and a history of trip results, learning how to manage data updates and UI notifications.

-Data Persistence with Gson: By utilizing Gson for converting Java objects into JSON and vice versa, I learned how to store and retrieve complex data structures, like lists of locations, in a format that could be easily saved in SharedPreferences.

-Algorithm for Shortest Route: I implemented a permutation-based algorithm to find the shortest route among several locations. This improved my problem-solving skills and understanding of algorithms for route optimization.

-UI Management: I honed my UI skills by working with fragments, layout managers, and views to build a fluid and interactive interface. This included updating the UI based on background calculations and input validations.

# Tools and Libraries Used->
-AirLocation: To get the user’s current location.
-Geocoder API: For converting place names into latitude and longitude.
-RecyclerView: For displaying the list of areas and route history.
-SharedPreferences: For storing data persistently.
-Gson: For converting Java objects to JSON and vice versa.
-Toast Messages: For user feedback when actions like adding a new area are performed.

# Future Improvements->
Implementing map-based visualizations of the routes.
Adding options for different fuel efficiency rates.
Allowing users to manually reorder locations to customize routes.
This provides a clear summary of your app, what it does, and what you learned during development. Let me know if you'd like any adjustments!


# App Link: https://drive.google.com/file/d/1y4UqNaxs1E_yC3rzFnsaamS6ex25my4S/view
