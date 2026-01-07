#  Real-Time Location Sharing App (MIT App Inventor)

This project is a simple real-time location sharing Android application built using **MIT App Inventor** and **Firebase Realtime Database**.

The app allows **two users** to share their live GPS location and view each other on the same map using markers.

---

##  Features

-  Get live GPS location from the device
-  Display user location on a map
-  Send latitude and longitude to Firebase
-  Track two users in real time
-  Show markers for both users on the same map
-  Auto-update location when data changes

---

##  Technologies Used

- **MIT App Inventor**
- **Firebase Realtime Database**
- **LocationSensor**
- **Map and Marker components**
- **Android GPS**

---

##  How the App Works (Logic Flow)

1. User enters a **username**
2. App reads GPS location (latitude & longitude)
3. Location is sent to Firebase under the username
4. Firebase triggers `DataChanged` event
5. If the data is from another user:
   - A marker is created/updated
   - Marker position is set using received latitude & longitude
6. Both users can see each other on the map in real time

---

##  Use Case

- Learning real-time databases
- Understanding location-based apps
- Beginner-friendly Firebase integration
- Foundation for tracking, delivery, or social location apps

---


##  What I Learned From This Project

- How Firebase Realtime Database works
- How to send and receive live data
- How to use maps and markers
- How to track multiple users
- Event-driven programming with `DataChanged`
- Basics of real-time location sharing

---

## Future Improvements

- Track more than two users
- Show user names on markers
- Add distance calculation
- Background location updates
- Migrate project to Flutter

---

##  Author

**Mansur Isah Madaki**

---

## License

This project is for learning and educational purposes.
