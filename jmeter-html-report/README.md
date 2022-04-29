# How to generate JMeter HTML Dashboard Report

# Introduction
This template will help you to generate JMeter HTML Dashboard Report, JMeter supports dashboard report generation to get graphs and statistics from a test plan.

# Technologies used
Performance Testing Tool- Apache JMeter
JAVA is prerequisite for Apache Jmeter so make sure that java should be installed.

## Steps For Execution

1. Clone the repository on your local system

2. Once you clone the repository, You will get one file
     a) blazedemo.jmx
     
3. put blazedemo.jmx inside bin folder(in JMeter)

4. Start JMeter and open blazedemo.jmx To run the test click the green play button on toolbar.

     a) Go to Tools -> Generate HTML Report then on Result File put the CSV file path where our result is stored 
     b) Then In User.properties file section mentions the location of the user.properties file 
     c) and finally In the output, directory put the newly created folder path.
     d) After that Click on Generate HTML Report button
     
For a better understanding, please refer to the blog:- 
https://blog.knoldus.com/how-to-generate-jmeter-html-dashboard-report-2/
