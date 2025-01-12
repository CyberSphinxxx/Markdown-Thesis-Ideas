
# Project Overview

## Title: CDO Jeepney Routes App

_This could also be made for own city_

**Objective:**  
To help residents and visitors navigate Cagayan de Oro City's public jeepney transportation system by providing real-time route information, jeepney stop locations, and user-friendly recommendations.

## Key Features

### Route Information:
- Display jeepney routes (e.g., R2, R1, etc.) with a list of stops and landmarks.
- Include an interactive map showing the full route.

### Real-Time Location (Optional Advanced Feature):
- Integrate GPS tracking for jeepneys to show their real-time location.
- Provide estimated arrival times at specific stops.

### Search Functionality:
- Allow users to search for routes by entering their starting point and destination.
- Recommend the best jeepney to ride and where to catch it.

### Jeepney Stops:
- Highlight designated jeepney stops and popular landmarks on the map.

### Offline Mode:
- Enable basic route and stop information to be accessible offline.

### Feedback System:
- Allow users to report issues, incorrect route details, or delays.

### Language Support:
- Provide translations in English, Cebuano, and Tagalog to accommodate diverse users.

## Development Plan

### Phase 1: Data Gathering
- Collaborate with local jeepney operators and the city transportation office to gather route details, schedules, and stops.
- Map out routes using tools like Google Maps or OpenStreetMap.
- Validate the data by riding the jeepneys to ensure accuracy.

### Phase 2: App Design and Development

**Frontend:**
- **Frameworks:** Use Flutter or React Native for a cross-platform mobile app.
- **UI/UX:** Design a clean interface with simple navigation and intuitive map features.

**Backend:**
- **Database:** Use Firebase or a SQL database to store route and stop information.
- **APIs:** Create APIs for fetching routes, stops, and user searches.

**Map Integration:**
- Use Google Maps API or Mapbox for interactive map functionalities.

**Real-Time Features (Optional):**
- Equip jeepneys with GPS devices.
- Use Firebase Realtime Database or MQTT for live location updates.

### Phase 3: Testing and Launch
- Conduct user testing with locals and visitors to refine the app.
- Release the app on Google Play Store and Apple App Store.

### Phase 4: Maintenance and Updates
- Regularly update route information based on feedback and city changes.
- Add new features like fare calculation or jeepney availability over time.

## Technologies to Use
- **Frontend:** Flutter, React Native
- **Backend:** Node.js, Django, Firebase
- **Database:** Firebase Firestore, PostgreSQL, MySQL
- **Maps:** Google Maps API, Mapbox
- **Real-Time Data:** Firebase Realtime Database, MQTT
- **Hosting:** AWS, Google Cloud, or Heroku

## Potential Challenges
- **Data Collection:** Ensuring route and stop information is accurate and up-to-date.
- **Real-Time Tracking:** Installing GPS devices in jeepneys may require partnerships with operators.
- **Adoption:** Encouraging people to use the app, especially locals who already know routes.

## Impact
- **For Residents:** Makes commuting more convenient, especially for those unfamiliar with all routes.
- **For Tourists:** Simplifies navigation within the city.
- **For Operators:** Provides insights into ridership patterns and potential optimizations.
