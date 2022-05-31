# Hello World Maven 

- This assignment should be done before the technical interview, as during the technical interview, you will be discussing it. 

Please see the assignment: 
1. Fix the job so it completes properly. 
2. Explain what the script is doing

# Helping a Customer
- Ensure your code / project  will compile correctly in a local environment
- It is also a good idea to "mirror" your environment with the customer environments.  
- - You don't have to do this everytime.  Sometimes you can see the typos or errors right away  
- Ensure all the commands invoked by your Jenkins agent/runtime have access to the specific runtimes.  For example install jq and solar scanner




# Here are the actual Steps I took to get this job running correctly. 
- Fixed  pom.xml file so code would compile locally. 
- 
- Updated Artifact Repository path 
- The demo software project will now build
- Installed the "jq" commmand the server : brew install jq
- Intalled Sonar Scanner : brew install sonar-scanner
- All the sh commands work. 
- Fixed Typo jq command "failsafeArgLine":"deploy",
- Updated the last two Stages step so they would run correctly. 
- Here is the  [Success Log](https://github.com/hughbrien/HelloWorldMaven/blob/master/success.log) 

