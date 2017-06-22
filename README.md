# Pond5
Selenium Automation of Footage 

Prerequisites
  1) Install Eclipse (Neon)
  2) Install Selenium (3.4.0 latest) - http://www.seleniumhq.org/download/
  3) Install TestNG - https://www.tutorialspoint.com/testng/testng_plug_with_eclipse.htm
  4) Install chromedriver (this is an exe used by the Webdriver to open a browser and run the tests) to your root directory on Windows. You will need to update Footage_Tests.java to point to the location of the binary (line 40) if you don't copy it to root. I ran my tests on Mac OS. 
  
  To Run as TestNG 
  1) In Eclipse, open git perspective and clone the git repo. 
  2) When the repo has been cloned to your local drive, switch to the Java perspective and import the project from git
    - select existing local repo (as you've already clone it)
    - select 'Import using the New Project wizard'
    - Select Java Project and select the same location that you used when you cloned the project. 
  3) You will see errors in the Project. You need to update the Build Path (Project -> Properties -> Java Build Path - Add External JARs - Add the selenium jar file and all the testng jar files to the path  
  4) select 'Run As - TestNG'. If you do not see this as an option:
    - Right click project and select 'Run Configurations' 
    - Select TestNG and select Class Radio button - Browse - you should see 'Footage Tests'. 
    - Click Apply and Run. 
  
  
