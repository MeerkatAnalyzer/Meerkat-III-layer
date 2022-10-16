# Meerkat Engine III Layer
At the last layer, Meerkat perform the most complex 
scans and predictions.   
The main idea of the third layer is 
dynamic analysis of the program behavior during runtime.  


## System and Memory scanning
<img src="system.svg" width=300><br><br>
The module responsible for the system and memory fuzzing uses American Fuzzy Loop (AFL++) to find undefined/undocumented behavior in code flow and unusual values in memory.  
For example, fuzzing can detect undocumented functions that perform abnormal behavior like file encryption or stealing user data. 


## Network scanning
<img src="mail.svg" width=150><br><br>
The network module is responsible for the dynamic network hypervisoring, and it's divided into two parts dedicated native and web applications.  
<br>  

### Native applications  
In the native solutions we are focused on scanning income and outcome packages especially:
- Content
- Source
- Destination
- Protocol
- Relation between sent packages   

A set of complex algorithms and Artificial Intelligence trained on the malware samples will detect unusual behaviour and report a supposed incident.

### Web applications
In the web application, we are focused on the API endpoint fuzzing and studying application behavior.

<br>

## Cloud integration   
  
<img src="cloud.svg" width=300><br>  
These days, most companies use cloud solutions.
The growing popularity of the cloud microservice architecture creates the field for new and more sophisticated attack technics that APT groups can use against companies.
To solve these problems everything you need to do is connect Meerkat Cloud Module to your cloud solution.    

Meerkat will be verifying: 
- Terraform scripts  
- SNS / SQS messages
- queries to S3 buckets   
- queries to the Aurora database   
and more!
