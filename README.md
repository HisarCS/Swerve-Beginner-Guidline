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

### Setting up your CANIvore(if you are using one(!RECOMMENDED!)

The CANIvore is basically a device which enhances the quality of your CAN connection. Using the CANIvore quite improves you CAN connection. Firstly, you have to obviously set up you CAN bus and connect the CANIvore to your CAN bus. Next, you have to connect to your robot either through ethernet or through wifi(via the radio). Then, you have to install the phoneix tuner from: https://store.ctr-electronics.com/software/ . Once the software is install press the button on the top left and select the CANIvore tab. If all the connections are perfectly up to standarts you must see this screen:


<img width="599" alt="Ekran Resmi 2024-02-12 14 17 05" src="https://github.com/HisarCS/Swerve-Beginner-Guidline/assets/120194760/e2275fc6-c03b-43a9-8edf-a03eb11bb293">

If you are not able to see the CANIvore either your CANIvore is broken(which is quite a small possibility) or there is a fallacy in your CAN connection. Please completely check your CAN connection make sure there aren't any loose wires or missing connections. Once you have fixed these issues you'll be able to see the CANIvore

Now that you are able to see the CANIvore you must set up a couple of things. You have to set up: the firmware if not up to the latest version, also you have to setup your CANIvore name to your liking(it'll be used in the code)


### Setting Up your CANCoders(if you are using CANcoder's)

CANcoder's are magnetic encoders which know the rotarary position of the swerve modules via communicating with the CAN bus. To set up your CANCoders you firstly have to connect them to the CAN bus, again you have to make sure that your CAN Bus is fully connected and on an acceptable level. Additionally, if you didn't buy the CANCoders pre soldered be sure you have perfectly soldered the CANCoders.

After you have checked the electronics and soldering connect to the robot via ethernet or wifi and open Phoneix Tuner

<img width="646" alt="Ekran Resmi 2024-02-12 14 58 37" src="https://github.com/HisarCS/Swerve-Beginner-Guidline/assets/120194760/15c5ec40-d789-4c6f-90e9-0c18b5066972">

Altough the CANcoders have different id's here the only id your's will have will be id zero which means not configured. To configure CANcoders you have to click onto the CANcoder rectangles on your screen. Once you do that you'll see a bar like the bar below on the left hand side of the screen.

<img width="175" alt="Ekran Resmi 2024-02-12 15 24 11" src="https://github.com/HisarCS/Swerve-Beginner-Guidline/assets/120194760/ea7a03ba-a218-4d70-8a53-877c58b481ac">

Here you firstly have to choose phoneix 6 from the dropdown menu write bove the update firmware  button and then click update firmware just to be safe. After that you have to set and ID via the ID input space and then click the set button. If you want to you can give your cancoder a named as well(not required, recommended).
