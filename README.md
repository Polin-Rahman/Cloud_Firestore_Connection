# Cloud_Firestore_Connection

Connect a new Android Studio project to Firebase with help of the Firebase assistant and add the Firestore dependency.
When that’s done i upload my first document into my first collection, by retrieving the user input from 2 EditText fields, saving the input as strings in a HashMap together with their keys, and passing this HashMap to Firestore over a database reference that get with the static Firestore getInstance method. For this simply call the collection and document reference methods on Firestore reference, pass strings for their names and lastly call the set method to pass Map to this reference and set it as the fields on first document. Also add an OnSuccessListener and an OnFailureListener to have callbacks about the upload success.

# Connection

* Open a project on Firebase console

(My project name is "conect" on my console)

* Select Datbase -> Cloud Firestore -> Creat database (in test mode)

* For connection uith Firebase realtime  Database in Android App (Android Studio) select Tools -> Firebase -> Analytics -> Log an analytics event

Then 

![Capture](https://user-images.githubusercontent.com/61315426/86616268-6a44f780-bfd7-11ea-9290-36909955266c.PNG)

# Add dependencies [in build.gradle(Module: app)]

implementation 'com.google.firebase:firebase-core:16.0.4' (added automatically)

implementation 'com.google.firebase:firebase-firestore:21.4.1' (need to add manually)

Then "SyncNow" & complete the process.

# API

 minSdkVersion 22
 
 targetSdkVersion 29
 
 # Database
 
 ![conect_firestore](https://user-images.githubusercontent.com/61315426/86617883-c577e980-bfd9-11ea-81df-44fdab8dbfe9.PNG)
 
 # UI
 
 ![conect](https://user-images.githubusercontent.com/61315426/86618419-b34a7b00-bfda-11ea-8144-fc6db65d2831.PNG)
 
 
 
