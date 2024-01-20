# Swerve-Beginner-Guidline

We are team 6431 from Istanbul Turkey and a team which is using the swerve drive for the first time(in 2024) like you which has visited this repo for help. This repo has all the issues we have faced through our Swerve rookie year and potential issue you may face as well. We are hoping that you find this repository helpful.)

### Setting up your Spark Max's ID

Spark Max's are motor controller commonly used on a swerve drive. Spark Max's are connected in a CAN cycle in a series connection so you can't ID them via the Roborio pins. You have to use a certain software: REV HARDWARE CLIENT to do that. Firstly, you have to connect a usb-c cable to the Spark Max's usb-c port. 

<img width="361" alt="Ekran Resmi 2024-01-20 21 22 17" src="https://github.com/HisarCS/Swerve-Beginner-Guidline/assets/120194760/65c57242-1264-488b-92d5-087d0251779e">

(usb-c port displayed here)

After the connection is esthablished a few seconds later the Spark Max will be visible on the REV Hardware client.

<img width="579" alt="Ekran Resmi 2024-01-20 21 24 08" src="https://github.com/HisarCS/Swerve-Beginner-Guidline/assets/120194760/5ae602f7-d548-489c-b697-50a7ca1223b3">

Here is how it appears. Altough it'll have an ID 0 because it isn't configured yet. When you click on the Spark Max you will see a screen like this:

<img width="752" alt="Ekran Resmi 2024-01-20 22 03 01" src="https://github.com/HisarCS/Swerve-Beginner-Guidline/assets/120194760/91ec412c-d9ba-4b87-aff6-31b3b803adbd">

This will appear if you have an up to date Spark Max if it needs an update an update screen will appear where you have to first do an update to acsess the main menu

In the main menu you'll have to change the CAN ID to be something other than zero and then scroll down to the bottom of the page to BURN FLASH. If you don't burn flash config wouldn't be saved.

### Setting up your CANCoders


