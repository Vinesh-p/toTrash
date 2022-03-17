
# To Trash

Hi! As a group of Computer Science students, we thought of addressing a daily-life problem, like consuming or using expired products. So we decided to team up to create an app, to store expiry dates of products and notify the user before expiration date. Though what we are making is simple, what makes this app **ToTrash** interesting is it's smart way of using Text recognization in Image Processing to store dates with one click from your camera button.  

## Video Demonstration 

Link: https://www.youtube.com/watch?v=7uH3e79BUpE

Camera Date scanner with calendar version: https://youtu.be/nD0q472h10g


## Branch Details 

We have different working branches for this totrash mobile application. As we are thinking to expland this project, we are constantly working on different branches

**master** : This version supports manual expiry date entry effectively. Use can also save the products with name, expiry date and display picture of it.

**UI_Integration** : This version allows users to directly scan expiry date and also scans barcode. 

**Calendar_Integration** : This version allows users to view a calendar screen displaying the expiration dates of items.

## COMPILATION INSTRUCTIONS 

- To create a flutter project 
``` flutter create totrash```
- To clone this project 
``` git clone git@github.com:schowda/totrash.git```
- To check different versions of it
``` git checkout [branch name]```
- To run the project successfully without any errors
``` flutter run --no-sound-null-safety```
- To build apk file, from root directory of project
``` flutter build apk --split-per-abi --no-sound-null-safety```
- special mention: This app is unstable in lates android version. 

