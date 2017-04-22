# Robosub-of-NACIT2016
This repository is the Source Code of NACIT team in Robosub Competition which is held on San Diego of California in July 25-31, 2016. I'm on duty of ImageProcessing and Strategy Control, our team named NACIT got the 11th in the competition, and the code has been provided here.

Scoring of the Final: 
http://robonation.org/sites/default/files/RoboSub2016%20Summary%20Scores%20and%20Rankings.pdf


# File Description
- Final Control & ImageProcessing Programs of NACIT2016: The source code of Strategy Control and Vision System
	- Source Code: Source codes
		- AUVAutoControl：The source code of Strategy Control(Based on Qt5)
		- VisionClass: The source code of Vision system(Based on C++ and OpenCV 2.4.9)
		- CustomizeFuntions: A set of customizes functions by myself
			- CustomizeStructs: Customized Structs (Customized by myself)
			- GeneralImageProcess: General Image Processing Functions (Customized by myself)
			- SpecialImageProcess: Image Processing Functions which point to Competition's Missions
			- SupportFunctions: Other Supported Functions
		- ThirdParty: the Third Parties including sensors' SDKs and the Library Files of OpenCV
		- XML Save Path: the XML Files saving the Experimental Data, and read by Programs
	- 调试小程序：SDKs written by myself just for convenience of debugging Vision System(Based on Qt5, so if you want to run the .exe file, you need include your Qt path in your environment variable)
- Control Program Introduction of NACIT2016.docx：Introduction of Strategy Control System(Written in Chinese)
- ImageProcess Program Introduction of NACIT2016.docx：Introduction of Vision System(Written in Chinese)
