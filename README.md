# Very Simple One-Touch Timestamp (on Launch) Creator/Recorder Web App

*15 Mar. 2025 Update: I now have an Android app (written in Kotlin): [Very Simple Launch and One-Touch-Add Timestamp Recorder Android App](https://raviswdev.blogspot.com/2025/02/very-simple-one-touch-timestamp-on.html). On Android mobile, the Android app is much faster than this repo's web app which has to run within a browser. But this web app is still useful on PC when one is working on PC and wants to quickly capture a timestamp. The duration between current timestamp and immediately previous timestamp feature lets one easily get the duration for a (typically small) task or a (typically small) break.*

This is a very simple one-touch timestamp creation/recording web app implemented as one single HTML file with JavaScript code in it. It will automatically create a timestamp (with no text associated with it) when the app is launched. The app will display a hardcoded maximum number of previous launch timestamps. It also has a button to clear the timestamps. I have added showing of duration between current timestamp and immediately previous timestamp.  

I need such a one-touch app on my Android phone (Samsung). In my limited search on Play Store, I could not get a free Timestamp app that does what I want as a one-touch operation. One app I tried needed three touches - to launch the app, to initiate adding a timestamp and finally a third touch to create the timestamp (with empty text).  

To setup this web app on mobile:
1) Copy the timestamp.html file to mobile (say via Gmail).
2) Move the timestamp.html file to a suitable folder on mobile (e.g. MyWebApps)
3) Open file in mobile Chrome (or perhaps other browser but I have tested it only on Chrome).
4) The app will run and show current timestamp. Later invocations of app will show previous launch timestamps.
5) To make the app easily accessible, add the timestamp.html file to Home screen.
6) You can also then add the Home screen file to Bottom Quick Launch (5 apps max on my Samsung Android phone).
7) Now it will be a one-touch (launch) timestamp recording mechanism (in browser Local Storage).


