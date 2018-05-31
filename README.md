# Dental Clinic Management System

A comprehensive set of tools for managing the entire workflow of a dental clinic, while offering a client oriented experience.

## Motivation

The motivation for coming up with this idea, was the lack of such a product in the market. There is a very small set of softwares who 
put emphasis in the customer experience, in things like appointment request facilitations, doctor communications and giving access to personal 
medical files.

## Features

- Set appointments from the app<br>
- Get realtime confirmations with push notifications and/or SMS<br>
- Access personal medical files and anamnesis<br>
- Pay treatments online<br>
- Communicate with the doctor and administrator from the app<br>
- Offline-first mobile app
- Handle non-registered users (appointments, treatments, seamless account merging)

## Software components

- Mobile app: Android (for clients and staff)
- Web app: NodeJS (for the administrator)

## Technology stack

* [Cloud Firestore](https://firebase.google.com/docs/firestore/) and [Realtime Database](https://firebase.google.com/products/realtime-database/) for data persistence
* [Cloud Storage](https://firebase.google.com/products/storage/) for storing files
* [Cloud Messaging](https://firebase.google.com/products/cloud-messaging/) and [Cloud Functions](https://firebase.google.com/products/functions/) for sending notifications and other backend triggered operations in the database
* [Twilio](https://www.twilio.com/) for SMS
* [Express framework](https://expressjs.com/) for Node.js
* [Web Sockets](https://socket.io/) for asynchronous communication in the web app

## Open Source Libraries used (Android application)

* [Tibolte/AgendaCalendarView](https://github.com/Tibolte/AgendaCalendarView) for the calendar
* [BlinkID/blinkid-android](https://github.com/BlinkID/blinkid-android) for extracting data from ID cards
* [firebase/FirebaseUI-Android](https://github.com/firebase/FirebaseUI-Android) for simpler authentication and storage 
* [bumptech/glide](https://github.com/bumptech/glide) for image loading and caching
* [chrisbanes/PhotoView](https://github.com/chrisbanes/PhotoView) full screen image viewer, with zooming support
* [JakeWharton/butterknife](https://github.com/JakeWharton/butterknife) view binding using annotation processing
* [rbro112/Android-Indefinite-Pager-Indicator](https://github.com/rbro112/Android-Indefinite-Pager-Indicator) indefinite pager indicator for RecyclerViews and ViewPagers
* [Someonewow/SubmitButton](https://github.com/Someonewow/SubmitButton) 
* [google/gson](https://github.com/google/gson) convert Java objects to JSON
* [facebook/Shimmer](https://github.com/facebook/Shimmer) shimmer effect on text and other views

## Open Source Libraries used (Web application)

* [FullCalendar.io](https://fullcalendar.io/) for the calendar
* [Socket.io](https://socket.io/) for realtime backend-frontend communication
* [firebase/FirebaseUI-Web](https://github.com/firebase/firebaseui-web) for simpler authentication and JWT validation 
* [JQuery-UI](https://jqueryui.com/) for frontend functionality enhancement
* [MaterializeCSS](http://archives.materializecss.com/0.100.2/) for the main UI design

## Versioning

* Git and GitHub for version control
* [Gradle](https://gradle.org/) for Android building and versioning

## Authors

* **[Arbli Troshani](https://github.com/arblitroshani)** - [personal log](https://github.com/arblitroshani/SEproj/wiki/Arbli-Troshani-Personal-Log)
* **[Gerd Alliu](https://github.com/galliu15)** - [personal log](https://github.com/arblitroshani/SEproj/wiki/Gerd-Alliu-Personal-Log)
* **[Enxhi Ferhati](https://github.com/eferhati15)** - [personal log](https://github.com/arblitroshani/SEproj/wiki/Enxhi-Ferhati-Personal-Log)
* **[Egi Gjevori](https://github.com/egjevori15)** - [personal log](https://github.com/arblitroshani/SEproj/wiki/Egi-Gjevori-Personal-Log)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
