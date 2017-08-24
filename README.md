 Readme:

PreRequirements:

Java 1.8
Eclipse 
TestNG
chromedriver executable file (I have saved in driver folder of the project)

import the Project and set up PATH as per requirement

Run the Project from testNG file.


Framework Structure :


Packages :

	Library : Will hold library files only.
	PageEvents : Will hold for all the events getting happen on a PAGE like HomePage.
	PageOjects : Contains the values and type for the elements of the PAGE.
	Test : Will  use PageObjects via PageEvents for completing actions.
	Utils: Contain all the base operations which wull happen all around the framework ,Will contain Reports as well.



	Next Can be added:

	Resourses : For Managing excel files and data reading 
	Properties : for instant solution of changing environment and other files
	DataProviders: For Providing data at run time


	
