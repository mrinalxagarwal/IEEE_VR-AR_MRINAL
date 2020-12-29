# IEEE_VR-AR_MRINAL
Created a software with the help of Unity and Vuforia assets to be able to print a 3D Model of Gandhiji on a Rs.500 note.

I used the Unity 2019.4.17f1 software and downloaded the Vuforia SDK online for the project.
Also, ceated and downloaded a database loaded from Vuforia with the image target being the Rs.500 note (downloaded from the internet). Also, making a new license key from Vuforia's site for the project.

Once we upload the files (database, 3D Ply Model, Vuforia SDK) onto Unity, delete the Main Camera from Unity and enable Vuforia AR Camera. Also, enable Image Targetting option under Hierarchy.
Choose the Image Target by going through the settings under Image Target Behaviour and choose the desired image for which the database has been uploaded. 

Drag the 3D Ply Model Asset folder from the Assets tab onto the Image Target section under Hierarchy and adjust the scale and position accordingly on to the Image Target. 

Change the Build Settings to make the program Android compatible. Change the package name, and check 'Vuforia Augmented Reality' under XR Settings under the main settings.

Click on Build and Run and download the APK file for the mobile applicatoin


