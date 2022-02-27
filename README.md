# Library Management Android App

This project is an Android application developed using Android Studio that can be used by users/admin to perform various Library related operations such as searching books, seeing books issued to the user, re-issuing books, adding/removing/updating books, collecting fines, etc. The App uses Google Firebase Cloud Firestore as the back-end database for storing details of books and users. Cloud Messaging is used to send notifications to users if a return deadline is approaching/fine is increased and when a new book is added to the Library by an admin. Cloud Functions are used to monitor the database and update fines, trigger notifications. The App has a user-friendly and interactive interface.

