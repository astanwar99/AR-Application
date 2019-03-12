# AR/VR-based Interior designing Android App 
### Description 

### General: 
Aim of our project is to enable customers to visualise how would a particular furniture set actually look in their home using 
Augmented reality. They can also select the furniture store they want by visualising their demo furniture setup using Virtual Reality.  

### Novelty: 
Virtual Reality is programmed in a manner that enables us to cover whole room with a mere 3 DOF VR-Headset (approx. 2000 bucks) 
which otherwise is possible only with highend headsets like Vive, Rift etc. We are using Scene switching for this.  
Augmented reality incorporates Ground detection simulation so even if the Phone doesn’t support ground detection then also 
application will work without any problem. 

### Tech-stack used: 
1.	C#  	 	 	 	 		 	 
1.	Unity 3-D 
1.	Android Studio  
1.	WikiTude SDK 
1. Google VR SDK 

### Hardware Requirements: 
1. VR-Headset  
1. AR-VR supported Smartphone 
 
## Project Modules 
 
### VR-Module 

*	This is the VR module. This is meant to be used by various furniture stores as a demo for displaying their furniture to users.  
*	Users can connect their phones even to a cheap VR headset and visualise the 360degree scene around them. When they want to move to next scene they just need to press a button in their headset. We have programmed this module in a way that Scene shifts on press of that button smoothly with 100% efficiency 
*	User can also interact with certain objects like globe (Spin), Taps (Open or Close), TV (On or Off) etc to give a more realistic feeling. 
*	There is a fixed lighting scheme maintained throughout with an appropriate blend of Natural and Artificial lighting.  
*	Coming to programming part, we have written 4 C# scripts AnimationController.cs ,Teleporter.cs, TriggerAnimation.cs, GazeInput.cs  as well as modified an already available WanderScript.js file. 

### AR-Module 
                                        
*	When the app is started, AR activity is started as shown in first image. Here user places the grid mesh on the ground by using the slider placed at bottom left to simulate Ground Detection. After this, user initializes the app by tapping ‘INITIALIZE’, located at bottom. 
*	After initialisation, a dock pops up at the bottom of screen containing various AR furniture models as shown in second image. User can select any model and augment it in the real world by dragging it on the screen. 
*	User can also change the size of object in real time by default gestures of zoom in and zoom out (third image).  
*	All this can be done in horizontal view as well to improve the immersion.  
*	In few cases, the device might lose calibration because of hardware limitation. User can tap ‘Reset’ button at top corner to restart the application. It changes the state of application as it was before being initialized. ‘Reset’ can also be used to try different arrangements of furniture in the room. 
*	User can repeat the procedure as many times as wants. 
