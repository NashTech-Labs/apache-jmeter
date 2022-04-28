# How to send Emails with JMeter SMTP Sampler

# Introduction
This template will help you to explain How to send Emails with JMeter SMTP Sampler. JMeter is the most popular performance testing tool so in this template we will see How JMeter helps us to send Emails with the help of SMTP Sampler.

# Technologies Used
Performance Testing Tool - Apache JMeter 
JAVA is prerequisite for Apache JMeter so make sure that java should be installed.

## Steps for Execution

1. Clone the repository on your local system

2. Once you clone the repository, You will get two files

	a) javax.mail.jar
	b) mailsender.jmx
	
3. Put javax.mail.jar inside lib folder (In JMeter) and also put mailsender.jmx inside bin folder (In JMeter)

4. Start JMeter and open mailsender.jmx

5. In jmx file, open SMTP Sampler and provide the Email Id's in "Address From", "Address To", "Auth Setting" 
Note -: In this jmx file I will not provide my Email Id so make sure before running test you should provide Email in SMTP Sampler

6. To run the test click the green play button on toolbar.

7. Now we can see the test result on "View Results Tree" under the Thread Group.

For a better understanding, please refer to the blog:-
https://blog.knoldus.com/how-to-send-emails-with-jmeter-smtp-sampler/
