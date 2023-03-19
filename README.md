# Onboarding Code Readme


This Android app is currently in development and has a feature to change the onboarding tutorial screens. This Readme will guide you through the onboarding code and provide instructions on how to make changes to the tutorial screens. 

# Understanding the Code
The code for the onboarding screens is located in the OnboardingActivity.kt file. This file contains the logic for displaying the tutorial screens and navigating between them.

# Changing the Tutorial Screens

To change the tutorial screens, you will need to modify the onboarding_pages.xml file located in the res/layout directory. This file contains the XML markup for the tutorial screens.

To add a new screen, simply create a new layout XML file in the res/layout directory and add it to the onboarding_pages.xml file by referencing it using the include tag.

To remove a screen, simply delete the corresponding include tag from the onboarding_pages.xml file. 

