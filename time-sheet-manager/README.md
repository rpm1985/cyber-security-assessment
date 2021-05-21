In this read me i will explain how to run my app so you can navigate to the branches.

First clone the app. 
 
Once cloned load into intellij.

next to run it click on gradle to the right and select the Tasks then build and click on assemble this will then 
assemble the app. If you use build it will fail due to some of the junit tests failing within the app and will stop 
you running it so you must use assemble.

once the assemble has completed you can go to the build folder select libs and from there you will see a jar file in 
there which you can right click and select the green play button that has run followed by the file name

once the play button is pressed a terminal will open up while it runs it and your looking for the port number which 
is port 8081 once you see that within the terminal towards the end of the intital run process. The application can be 
accessed then from a webpage in google chrome via the following address: localhost:8081/login.

Be warned!!! that when you switch to the branch names which you will find within the report you will have to change the 
address to https://localhost:8081/login due to one of the security measures I implemented. 

When you are testing the branches, all you need to do is to click the bottom right where it says Git: master and it will 
open a box where you will be able to change to any of the branches listed within the report.