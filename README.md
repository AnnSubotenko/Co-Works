                                                                                              Project Overview:
The project is a co-working space booking platform developed using Ruby on Rails as the backend framework, Stimulus.JS for dynamic frontend interactions, Progressive Web App (PWA) features for enhanced user experience, and QR code scanning for streamlined check-in. The primary focus is on facilitating users in finding, booking, and checking into co-working spaces in Berlin.

Technical Features:
1. Map Integration:

- Implemented a dynamic map using a mapping library (e.g., Leaflet or Google Maps API).
- Integrated geolocation to show the user's current location on the map.
  
2. Marker Customization:

- Developed functionality to change marker colors dynamically.
- Implemented a feature where the marker for the user's current location turns dark blue when selected.

3. Keyup Search:

- Integrated a keyup search functionality for users to easily find co-working spaces by typing in keywords.
- Utilized AJAX requests to update search results in real-time.

4. Check-in Functionality:

- Implemented a check-in system allowing users to check in upon arrival at the co-working space.
- Utilized Stimulus.JS controllers to manage the check-in process asynchronously.
- Incorporated QR code scanning for a quick and efficient check-in experience.

5. Booking Calendar:

- Integrated a booking calendar for users to schedule and reserve co-working spaces.
- Leveraged Rails for backend handling of booking requests and availability management.

6. PWA Features:

- Implemented Progressive Web App features to enhance the overall user experience.
- Enabled offline functionality, allowing users to access certain features even without an active internet connection.
- Utilized service workers for background synchronization and caching of critical resources.
