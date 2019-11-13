# AMSJmeterScript

This is a load test plan for AMS open APIs. These are all Get APIs and does not require any header. 
Base URL: https://staging.ams.prolific.io

Instruction: Please make necessary changes in the Thread group before triggering the test. 

How to run this file?
> Open the file using Jmeter and run the plan.

How to run in NonUI mode?
> Navigate where the .jmx file is present. Run below command:
  jmeter -n -t <<testfile.jmx>> -l <<logfile.jtl>>

The above command is going to run the whole script in not UI mode and would generate a log file. 

How to read the log file?
> Open the log file using any of the Listner in UI mode.

Note: In order to edit the load please open the file in Jmeter. Edit the necessary changes in Thread section. Save the changes. Run either in UI or NonUI mode. 

Note: Please make sure to change the path in the "CSV Data Set Config" before running the report extractor. 


Author: Debabrata
Email: debabrata@heady.io
 
