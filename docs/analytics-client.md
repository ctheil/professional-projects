# Analytics Client: RFID-Driven Analytics for iPadOS

## Overview

**Redefining Analytics with RFID Technology!** 
The Analytics Client is a groundbreaking application developed for Apple iPadOS, tailored for the University of Colorado Denver's Learning Resources Center (LRC). By leveraging RFID technology, it offers a robust and secure way to track detailed analytics, ensuring accurate and verified data collection.
## Features
### RFID-Driven Session Check-In
- Seamlessly integrates with RFID technology to pull real-time schedules and populate a user-friendly interface.
- Students can effortlessly check into sessions, with their university ID being used as a verified identifier, ensuring accurate and secure data collection.
### Unique UX Challenges & Solutions
- Designing an internal application for iPadOS presented unique UX challenges, especially with the RFID scanner being recognized as a keyboard.
- Innovative solutions, such as omitting the search bar, were implemented to ensure a seamless and intuitive user experience.
### Secure Authentication & Device Management
- The application employs a unique authentication system to prevent unauthorized access.
- Devices are uninitialized by default. Upon installation, a device document is created in the MongoDB database, assigning a UID stored in the device's local storage.
- This UID is linked to a token, allowing administrators to manage device access via the LRCo admin interface. Admins can verify new devices and blacklist unverified ones, ensuring data security and integrity.
### Integration with LRC API
- The core logic and data management of the application are handled by the LRC API, ensuring seamless integration, real-time updates, and scalability.
## Dive Deeper

The Analytics Client is more than just an analytics tool; it's a revolution in how educational institutions can track and manage data. By merging RFID technology with the power of React Native and Expo, this application offers a secure, accurate, and user-friendly solution to the LRC's analytics needs. The unique challenges faced during development, from UX design to secure authentication, showcase the adaptability and innovation that went into crafting this state-of-the-art application.---
