# ChatNow
This is a one to one native android chat application built in Java and XMl, Firebase is used for backend and all the user registration , user authentication ,
message send/receive and user-message database is maintained using Firebase.</br>
This app contains search options where you can search all others and choose to chat with them, it also has the profile feature with which you can change avatar or
even can upload your own picture.</br>
This app also provides the message sent- delivered and seen feature which helps you to chat efficiently with your friends and family.




### How to use this chat app in your project : 

I have deleted google-services.json. Add yours
<br> Change Authorization:key with your key from firebase project</b>

###### Implementation Guide 
</br>
<br>1 - Open this Project in your android studio
<br>2 - *IMPORTANT* Change the Package Name. (https://stackoverflow.com/questions/16804093/android-studio-rename-package)

###### Firebase Panel
<br>- Create Firebase Project (https://console.firebase.google.com/);
<br>- Import the file google-service.json into your project
<br>- Connect to firebase console authentication and database from your IDE (video 2)
<br>- In firebase Storage Rules, change value of "allow read, write:" from "if request.auth != null" to "if true;" (video 12) 
<br>- For sending notification, paste your Firebase project key into your project APIService.java (video 18) 
<br>- When you change database settings, you likely will need to uninstall and reinstall apps to avoid app crashes due to app caches.

###### Feel free to point any bug and remove it and create a issue, Also if you liked the project please star.




