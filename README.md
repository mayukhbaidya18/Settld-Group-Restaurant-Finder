# SettleIt

SettleIt is an iOS app designed to help groups of friends find the most convenient restaurant or location when they are situated in different places. The app ensures everyone travels a fair distance by calculating the optimal meeting point for the group.

## Features

### 📍 Optimal Meeting Point
* One member of the group manually enters their current coordinates.
* The app calculates the location that minimizes the maximum distance from all group members using the Minimum Enclosing Circle algorithm (Welzl's algorithm).
* Ensures no one has to travel significantly more than others.
* Displays the selected location along with travel distance and time for each user in a clear, sorted format.

### 🗺️ Apple Look Around Integration
* Provides a 3D street-level preview of the destination using Apple's Look Around feature.
* Helps users visualize the location before heading out.

### 🚗 Individual Routes
* Shows individual paths for each user on the map using PolyLines.
* Each route is clearly marked so users know exactly where to go.

### 🔍 Location-Based Search
* Users can set a search region on the map.
* Supports searching for restaurants, malls, schools, hospitals, and more using Apple's built-in Natural Language Query.
* Search results are displayed directly on the map for easy navigation.

## Demo



https://github.com/user-attachments/assets/74f4a8fe-4507-4fed-bbcc-bcd60961a4cf


https://github.com/user-attachments/assets/605baccd-cb22-4cdd-b185-bbcf0ec3d588




## Technologies Used

* Swift & SwiftUI
* MapKit & CoreLocation
* Apple Look Around
* PolyLines for route visualization
* Minimum Enclosing Circle algorithm (Welzl's algorithm)

## How to Use

1. Enter your location coordinates manually.
2. Add your friends' locations.
3. The app calculates the optimal meeting point.
4. View the recommended restaurant/location along with travel details for each user.
5. Optionally, explore the destination using Look Around or search for nearby points of interest.

## Installation

Download SettleIt from the [App Store](https://apps.apple.com/us/app/settld-group-restaurant-finder/id6748634598?platform=iphone) to get started.

## License

2025 Mayukh Baidya

## Website

(https://settld.space/)
