Push Notifications Tutorial
===========================


- FH = In feedhenry studio
- UA = On UrbanAirship website
- G = Googles Api Console

Steps to Setup
--------------

1. (FH) Clone PushTest into studio (git@github.com:Crosbie/PushNotificationTester.git)
2. (UA) Register account with UrbanAirship
3. (UA) Create new App in UrbanAirship (push enabled), fields can be left blank for now
4. (G)Enabled a Google API Console https://code.google.com/apis/console/
5. (G) Enable Google Cloud Messaging for Android
6. (G) API Access - Create new Server key (no IP addresses)
7. (UA) Edit app to include Google API key, and FH app package name (config/Android)
8. (FH) Enable Push Notifications, copy Application Keys from UA
9. (FH) Get Google Project number from API console (Overview)
10. (FH) Build Android app
