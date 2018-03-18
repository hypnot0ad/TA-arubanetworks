Splunk Technology add-on to enhance the syslog messages indexed from Aruba Controllers and Instant Access Points.

Currently this TA is under construction/work in progress/pre-release. Please contact me if you wish to use this TA.
This TA will take syslog data streams (preferably from a universal forwarder) and name its sourcetype as either; aruba-controller (for controllers), and aruba-iap (for instant APs) and place it in the aruba index.

Version 0.1

Features:
- Sourcetypes and Indexes have been defined
- Field extractions for Error Subsystem, Error Numbera and Error Severity

To Do list:  
- Field extraction to extract the error message.
- CIM compliance...
