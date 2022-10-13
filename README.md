# Meerkat Engine III Layer
At the last layer Meerkat perform the moste complex 
scans and predictions.   
The main idea of the third layer is 
dynamic analysis of the program behavior during runtime.  


<!-- ## System operations scanning -->

## Network scanning
<img src="mail.svg" width=150><br><br>
Network module is responsible for the networking Hypervisoring, and it's devided into two parts dedicated native and web applications.  
<br>  

### Native applications  
In the native solutions we are focused on the scanning income and outcome packages especially:
- Content
- Source
- Destination
- Protocol
- Relation between sent packages   

Set of the complex algorithms and Artificial Intelligence trained on the malware samples will detect unusual behavior and report supposed incident.

### Web applications
In the web application we are focused on the endpoint fuzzing and studying application behavior.  
<br>

## Cloud integration   
  
<img src="cloud.svg" width=300><br>  
This days most of the companies uses cloud solutions.  
Growing popularity of the cloud microservice architecture creates field for the new and more sophisticated attack technics that APT groups can use against companies.  
To solve this problems everything what you need to do is connect Meerkat Cloud Module to your cloud solution.    

Meerkat will be verifying: 
- Terraform scripts  
- SNS / SQS messages
- queries to S3 buckets   
- queries to Aurora database   
and more!