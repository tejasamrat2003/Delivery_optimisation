#**Delivery Route Optimization with Customer Clustering Based on Time Slots and Location**

This project aims to optimize delivery routes by clustering customers based on their preferred delivery time slots and geographic locations. The system generates simulated customer data, organizes them into clusters, and finds efficient delivery paths to minimize travel time and enhance operational efficiency. By integrating OpenRouteService, real-time travel data is used to adjust routes based on actual conditions, providing a practical solution for delivery optimization.

#**Key Features:**
Customer Data Generation: Simulates random customer data with geographic coordinates and preferred delivery time slots within a specified radius.

Clustering by Time Slot and Location: Clusters customers based on both time-slot preferences and geographic proximity to streamline delivery scheduling and reduce travel distance.


Optimized Delivery Routes: shows different paths available that can be used by various algorithms to find the efficent path.

Real-Time Travel Time Data Integration: Uses OpenRouteService API to fetch travel times between locations, ensuring route optimization reflects real-world conditions.
Project Overview
#**The project is structured as follows:**

Simulate Customer Data: Generates customer details such as location (latitude and longitude) and preferred delivery time slots. This data forms the basis for clustering and route optimization.

Customer Clustering: Groups customers based on their location and selected time slots using K-Means clustering, ensuring deliveries are grouped logically by area and timing.


