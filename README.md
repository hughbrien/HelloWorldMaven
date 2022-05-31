# Hello World Maven for Interview

Please see the assignment: 
1. Fix the job so it completes properly. 
2. Explain what the script is doing

# Jenkins Job Description
This Jenkins job is doing the following:
- Checks out a project from https://github.com/hughbrien/HelloWorldMaven. 
- - I  [forked the project](https://github.com/hughbrien/HelloWorldMaven) so I could track all the [changes](https://github.com/hughbrien/HelloWorldMaven/commits/master)
- The job then executes a series of /bin/sh scripts
- Generates a json file 
- Parses the generated file to access specific parameters for the maven build
- Calls mvn with build parameters.  
 
# Notes on Assisting Customers
- Here are some good tips  
- Ensure your code / project will compile correctly in a local environment
- If possible, it can be a good idea to "mirror" your environment with the customer environments. Especially for complex problems 
- Ensure all the commands invoked by your Jenkins agent/runtime are installed in your environment.
- Ensure Jenkins has access via appropriate PATH variables
- Ensure the CI/CD Environments are complete
- Recommend ways to optimize and simplify the building process by using or NOT using specific plugins. 


# Actual Steps and Changes 
- Fixed  pom.xml file so code would compile locally. 
- Updated Artifact Repository path 
- The demo software project will now build
- mvn clean compile test deploy all work correctly.
- Installed the "jq" command the server : brew install jq
- Installed Sonar Scanner : brew install sonar-scanner
- All the sh commands work. 
- Fixed Typo jq command "failsafeArgLine":"deploy",
- Updated the last two Stages step so they would run correctly. 
- Here is the  [Success Log](https://github.com/hughbrien/HelloWorldMaven/blob/master/success.log) 


