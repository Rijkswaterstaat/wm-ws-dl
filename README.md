# wm-ws-dl
Rijkswaterstaat (RWS) policy is to give access to as much data as possible, both technicaly and juridicaly.<br>
Data from the waterquantity and waterquality network are stored and can be accessed by a GUI https://waterinfo.rws.nl.

Beside the GUI, measurement data available at the data distributielaag (wm-ds-dl) can be accessed by programmers.
To get acces to the data RWS provides a variety of Web APIs described in Slate.
Please use the Slate documentation deployed on this git to get any further information to communicate with the Web API.
Beside a OGC compliant webservice, a set of Rest API services can be found to get access to;
- Actual measurements
- Predictive measurement
- Historical measurements
Please note that all data is originaly collected from and stored in different systems and therefor can have different code based end-points. Esspacialy historical and actual en predictive measurements.
<br>
Please be aware of the discaimer (in Dutch) using the data and Web API https://www.rijkswaterstaat.nl/footer/index.aspx.
<br>
<br>
As you know..<br>
Web APIs serve as a means of communication between consumers and a provider. Both support XML-based data payloads,
but JSON is the more common payload type for web APIs. When comparing web services to web APIs, 
the significance lies in the amount of work that has to be done by the consumers and provider to get access to the data; 
this is a process known as serialization and deserialization, respectively. Serializing
and deserializing JSON in a web API scenario typically requires far less work which, in turn, 
equates to better performance and fewer compute cycles. This is one reason why web APIs are great for 
information transfer on mobile devices and tablets; as opposed to on desktops and services, 
where they have restricted processing environments.
Conversely, web services facilitate interactions between two systems, 
and almost always depend on an XML like interface to communicate with each other. 

In terms of what web APIs and web services have in common, both are essentially a means to an end 
and the same problems can be solved by both. And both can be configured to operate over a network or within a machine.
But the approaches of each come with their own pros and cons.  
For now, web services are a service from one device to another; 
they communicate over the Internet and are optimized for machine-to-machine communication, 
meaning that machine-readable files and formats (like XML) are easily transferable. 
APIs are software-to-software interfaces with an abstract set of verbs instructions for accessing web-based applications. 
Whatever you wanted to accomplish with a web API can be accomplished with a web service; 
web services are merely predecessors in the evolution of web integration methodologies.
<br>
<br>
“You can have data without information, but you cannot have information without data.” 
– Daniel Keys Moran, an American computer programmer and science fiction writer.
