Metro Route Optimization System
This project is a Java-based metro route optimization tool designed for users to plan their metro journeys efficiently. The system offers a variety of features, including selecting starting and destination stations, finding the optimal route, exploring alternative routes, modifying routes mid-journey, and applying senior citizen discounts.

Features
1] Station Selection:
Users can choose their starting and destination stations from a predefined list of metro stations in Delhi.
The stations are hardcoded for simplicity and represent key locations in the metro network.

2] Optimal Route Calculation:
The program uses Dijkstra's Algorithm to compute the shortest route between the selected stations based on distance or travel time.

3] Alternative Route Suggestion:
Users can view an alternate route using the Breadth-First Search (BFS) algorithm, offering another viable option for their journey.

4] Dynamic Route Modification:
Users can change their route mid-journey by selecting a new destination. The system recalculates the optimal route from the current station.

5] Senior Citizen Discount:
Passengers aged 60 or above are eligible for a special discount, applied automatically based on the age entered by the user.

How to Use

1] Launch the Program:
Compile and run the program using a Java IDE or command line.

2] Select Stations:
Input the name of your starting and destination stations from the list provided.

3] View Routes:
The system will display:
The shortest route (using Dijkstra's Algorithm).
An alternative route (using BFS).

4] Change Route:
If required, you can select a new destination mid-journey, and the system will recalculate the route.

5] Enter Age:
Provide your age when prompted. If you are 60 or above, a discount will be applied to your travel cost.

6] View Travel Details:

The program displays the final route, travel cost, and any applicable discounts.
