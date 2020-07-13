# kyle-skyllingstad-SHIFT-Furniture-Mobile-Application-Controller
SHIFT Furniture iOS Application Overview

The SHIFT Furniture mobile application is an interactive user application that can control the motion of SHIFT Furniture’s autonomous furniture-moving SHIFT Pod System. SHIFT Furniture is comprised of a collection of 6” by 6” by 3.5” square units called SHIFT Pods that, when manually placed under pieces of furniture, can move them to where the user wants them, when the user wants it. The user application can be uploaded and run on any iOS device, such as an iPhone or iPad. This application allows the user to control his or her SHIFT Pods with spoken or written definitive commands, such as, “Move my couch four feet to the right,” or “Angle the piano 45 degrees to the left.” When commanded, the chatbot uses Google’s Dialogflow A.I. capabilities to take in the request, process it, and send it through WiFi to the Pods to execute. Upon reception and validation of the user request, the mobile application will present the command it is sending to the Pods onscreen in the form of written text as well as spoken words. Then the user can watch the Pods move their furniture from its current spot to its desired location. Users should try to avoid unexpected obstacles whenever possible to avoid safety and mechanical hazards, but try not to worry, because the optical sensors installed on every Pod allow them to simultaneously analyze their environment and stop all motion of unexpected obstacles suddenly begin to impede their path of travel. Safety is SHIFT Furniture’s highest priority.



Instructions for SHIFT Furniture’s iOS Application Use


Getting Started

To move furniture, users must have at least four SHIFT Pods, two of which must be motorized. Those two will be connected by a telescoping rod to allow easy, stable alignment, and the other two can either be motorized and attached in a similar manner, or unmotorized and linked to each other by a similar adjustable rod. Essentially, the user must have at least one set of twin motorized Pods and enough other sets of motorized or unmotorized Pods to bring the total to two sets, or four Pods, per furniture piece, big or small. For larger pieces of furniture such as a couch or large dining table, three sets (six SHIFT Pods) would be ideal for moving, with at least one set being motorized. 

Before placement underneath furniture, the user must first locate the lead SHIFT Pod in each set of motorized Pods being used. This Pod is demarcated by a blue power button as well as a space allowing for its host microcontroller to be plugged in with a micro USB cable. The user must first find the lead SHIFT Pod in each set and make sure it is adequately charged by viewing the blue power bar next to the power button. Once the user has found this lead Pod for each motorized set, he or she must plug each of them into a personal computer (Mac or PC) one at a time through the micro USB port. Once plugged in, the user then must press the power button twice quickly to prompt the computer to open a browser requesting the entering of the user’s personal WiFi network name and password. Here, the user must enter his or her credentials, and hit proceed. Then, the browser should return a unique assigned internet protocol “IP” address assigned to the lead SHIFT Pod unit. The user must take a note of this for each powered SHIFT Pod pair, as it goes into the iOS application in order to sync the application with the SHIFT Pod system. After taking note of each SHIFT Pod’s IP Address, the user is ready to unplug the SHIFT Pods and mount them underneath furniture. 


SHIFT Pod Placement

For placement, users must place the two connected motorized SHIFT Pods underneath the heavier side of his or her furniture, and the other two underneath the lighter side. Users should place the SHIFT Pods so the front side of them, indicated by a black arrow on top of each Pod pointing forwards, align with each other and are facing forward. When controlled, all motion of the Pods will be in alignment with the direction of these arrows. In other words, if the Pods are commanded to move three feet to the right, they will turn ninety degrees to the right from the direction the arrows were previously facing, and then they will move forward four feet in the direction the arrows are now facing. This is the reference compass of the Pods. Users should take note of this before placement so the Pods move as expected. Once Pods have been placed underneath the furniture, they will be held in place securely by high-friction rubber padding. All the user must do is turn them on by pressing the power button, and they will automatically connect to WiFi now that the host control code is uploaded. All the user must do is periodically watch the power bar on the side of each Pod to make sure they are not out of battery life, and he or she should be good to go! 


Getting the App Running

Now the user is ready to begin commanding the Pods. If downloading from the app store, a user can skip these steps and simply download the SHIFT Furniture App to get started moving furniture. 

Otherwise, he or she must complete certain steps to successfully install the application on his or her computer or mobile phone. To do so he or she should follow the following steps to command the mobile iOS application. 

1.	Make sure he or she has a Mac with Xcode installed. If not, users can easily install it on an existing Mac, or install it on a virtual machine on a Linux machine or PC.
2.	Download the app master file from the GitHub, SHIFT Furniture App, onto the Mac or virtual Mac. Unzip the compressed file.
3.	Open terminal in your Mac or virtual Mac, and in the default user directory, type the following command: sudo gem install cocoapods. If any errors arise, most likely your OS is not up to date. Check the CocoaPods website for further details regarding how to proceed from here.
4.	Once CocoaPods has successfully installed, change the directory to the location of the contents of your unzipped SHIFT Furniture App project files including the podfile.
5.	Type the following command: pod install. This should create/update a file in the SHIFT Furniture App project folder – SHIFT.xcworkspace.
6.	Open this file, SHIFT.xcworkspace, in Xcode on his or her Mac or virtual Mac (in the case of Linux machine or PC).
7.	Plug his or her iOS device into the computer. Wait for several seconds.
8.	In Xcode, the user should see the SHIFT Furniture program code. On the far upper left of the screen, the user should see two blue Xcode folder files, each with dropdown menus, labeled SHIFT Furniture and Pods, respectively. If he or she only sees a dropdown option on the Pods folder, but not on the SHIFT Furniture folder, he or she must close Xcode, delete the .xcworkspace file, and reinstall the podfile back in Terminal as done previously.
9.	Once both file folders have dropdown menus, the user must then click on the SHIFT logo icon at the top of the page just to the right of the darkened square button. This will show him or her a list of devices to run the app on, and the user should scroll to the top and select his or her mobile device, which should show up there once connected. This may require the user to unlock his or her phone in order to make it available to be trusted by the computer.
10.	Once his or her phone has been selected, the user can then upload the SHIFT Furniture iOS application to his or her phone by pressing the triangle button to the left of the square one. Xcode will prompt the user for his or her computer password, and he or she should enter it as many times as necessary to proceed through the inquisitions. The user may need to change a few settings on his or her iOS device to allow it to run the app, if prompted to do so on the screen of his or her device. Here, the user must enter permissions and change settings as directed.
11.	If the app uploads properly, Xcode should print a popup window displaying a hammer and saying, “Build Succeeded,” to indicate successful compilation and uploading of the code. If instead a window pops up saying, “Build Failed,” the user should make sure his or her iOS device is updated to the newest version of iOS. Once this has been corrected, the application should build successfully.
12.	The user then can go to his or her iOS device and open the SHIFT Furniture mobile application! All he or she needs to do here is input the IP Address of each lead Pod when requested, and he or she is ready to control them via WiFi. Simply follow the onscreen instructions to get started!


I wish you the best SHIFT Furniture experience shifting the way you view your living space and how you think about moving your furniture. Feel free to reach out to me at skyllink@gmail.com if you have any questions or concerns regarding how to run SHIFT Furniture, or if you have any unexpected errors while trying to run, or if you just wish to hear the latest news on our furniture-shifting movement. Best of luck, and happy moving!

