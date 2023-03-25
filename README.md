# Android-Weight-Loss-App
Tavo's Weight Loss App is a simple Kotlin/Android Studio project that demonstrates the creation of activities, events, buttons, and text views in an Android app. The app is designed to track weight loss progress and encourage healthy habits.
#########################################################################################################################

Introduction
Tavo's Weight Loss App is a Kotlin/Android Studio project that aims to track weight loss progress and encourage healthy habits. The app consists of three activities: Main Activity, Client Info, and Submitted Info, each with their respective event-driven flow.
#########################################################################################################################

Main Activity
The Main Activity is the first screen the user is introduced to. It displays an ImageView of athletic silhouettes and a Start button that takes the user to the Client Info activity. If the user has already entered their information, they have the option to continue (currently not working).
#########################################################################################################################

Client Info
The Client Info activity collects basic information from the user, such as their first name, height in feet/inches, start weight, and goal weight. The user has the option to submit their information with a Submit button or go back to the Main Activity with a Go Back button. If the user inputs units that are not realistic for a human being's physical nature, Toasts will show up.
#########################################################################################################################

Submitted Info
The Submitted Info activity displays the user's name and current weight in a bold textview. Other textviews provide information such as the number of days it will take the user to reach their goal weight and an estimate of their Body Mass Index (BMI). The user can update their weight using the linear layout edittext and button. When the user updates their weight, a toast shows up to congratulate them. Another toast will appear when they reach their weight goal.
#########################################################################################################################

Future Improvements
One area of improvement for the app is the implementation of a database to store the user's information. Currently, if the user exits the app or tries to go back to the homepage, all of the data they input is lost.
