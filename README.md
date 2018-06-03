# Assignment1
 The task fo this assignment was to develop an application that can accept XML as inputs reads the file and Output the resul or responses in XML format.
 The element of the XML will be read by the developed applcation to perform some validation and returns a response messages. 

# Application Description.
 
 This application was designed in JAVA that uses Java Virual machine ( JVM) for the compilation of codes for the Machine Language. 
 The Developed a plication has the following functional capability:

 a) Authentication of users request
 b) Validation of request order against records in the database 
 c) Generation of XML file ofr response Message.
 

# STEP-BY-STEP OF THE APPLICATION RUN

  To execute the developed applcation the below steps needs to be followed:
 	
	a. Download the developed  application into a  folder (Assignment1) in  any directory of the computer i.e  C:\Users\Owner\Desktop\BACK-TO-SCHOOL\QUALITY ASSURANCE\ASSIGNMENT\Assignment1/
	
 	b. Open RUN application( windows + R buttonon) on windows type 'cmd'and press Enter button. The windows commnad prompt will open.
	
	c. Type cd <<pathfile of the downloaded applcation on the system >> e.g  cd  C:\Users\Owner\Desktop\BACK-TO-SCHOOL\QUALITY ASSURANCE\ASSIGNMENT\Assignment1/
	
	d. Copy the xml file (either incomingOrder.xml) in the same directory for e.g. A:/CS/Courses/QA/Assignment/Assignment-1/
		
	e. Type java -jar assignment1.jar on the command prompt to run the program. This execute the application Jar and prompt users to enter the name of the XML file and press Enter button
	
	
	
# Sample Reponses
If the xml file path and structure is valid and the part number and quantity are valid?, the system return the following responses;
	{File {authorizedMsg.xml} saved to directory ==> }
	{Authorized!}
	xml file is valid - true
    {File {partResponseSuccessMessage.xml} saved to directory ==> } 
Also, it writes the respective response for security and partmanager an xml files.

# Validation Messages
The system cannot find the file specified - If the system is unable to read valid xml from the user
Tag not properly closed - System throws this message if any of the xml tag is not closed i.e The end-tag for element type "partnumber" must end with a '>'

# Code Examples
