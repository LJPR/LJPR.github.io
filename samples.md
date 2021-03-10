
###Past Work Samples


Excerpt: Technical Overview for a Silicon Valley Initiative proposal. 

>The following is an overview of the CHAMP architecture. Our system uses a IoT (Internet of Things) control module which is responsible for gathering all the relevant data from the sensors on the harness or collar. The module then transmits the collected information to an EC2 (Elastic Computing) server in the AWS (Amazon Web Services) cloud via the MQTT protocol which has become the standard in the IoT industry. The data transmitted over MQTT is encrypted via SSL (Secure Socket Layer). The medium for the transfer is either a 2G phone connection maintained by the control module or a WiFi hotspot that is setup by the user. The WiFi connection is used as a backup in case the 2G connection fails. The failover process is automatic. Once the data has been transmitted to the server, it is read by our web service which stores the data in a RDS (Relational Database Service) database. This can be accessed as a download via our CSVReporter web service. Simultaneously, a client/handler can login to the IoT web service running in the server to view a live data stream of the present status of the service animal. The web service is secure, running through HTTPS(HyperText Transfer Protocol Secure) and is accessible from a phone, tablet, or a computer. The system is illustrated in Figure 1 below.


Excerpt:  Educational Material on Cognitive Bias.

> One of those is confirmation bias. We all know the rhyme that starts “Roses are red, violets are blue”. Confirmation bias occurs when you remember Valentine’s Day, when you see a lot of red roses- and you don’t pay attention to any of the times you see yellow or white roses. So you are confirming the statement you already know- that roses are red- without noting that roses can be other colors, too. Many cognitive biases come from the human desire to keep believing the same thing. There is a lot of information out there! So it is natural for us to only look for information that we think is important to us- that is, information about the things we already care about. Wanting to keep believing the same things is called cognitive inertia. The rhyme also tells us that “violets are blue”. But it might startle some of us to hear that violets are usually purple.  As we can all be stubborn sometimes, you might say “Well, they look blue to me”. It can be hard to change your mind after such definitive statement, even if someone shows you a picture of purple violets, or gets others to tell you that they’ve seen purple violets, too. You may even think to yourself, even if you’ve never thought about it much before, “Violets are definitely blue, I’ve seen it myself”. When you still believe something even more after someone shows you that something is wrong, that is called the backfire effect.


Excerpt: Rebuttal to Issues Raised in Proposal Meeting, Anonymized

> In response to the question of sensor validity and the use of ambient temperature and humidity in interpreting the core temperature of the animal: we have found that the current guidelines for canine comfort as established by the 2014 USDA standard for service animals set out primarily guidelines for ambient temperature. Core temperature inferred from anal temperature is a significantly invasive diagnostic tool. Recording both ambient and contact temperature allows us to gain complete understanding of the dog’s temperature and environment, and has been used as a diagnostic in many scenarios, including the study Regional Skin Temperatures Associated with Total Sympathetic Blockade in Conscious Dogs, J. Peters et al, the British Journal of Anasthesia, 1988. Additionally, in Comparison of rectal and axillary temperatures in dogs and cats, 2014, Joana B. Goic, DVM et al. at Department of Small Animal Clinical Sciences, Michigan State University, found that axillary temperature is positively correlated with rectal temperatures, with a median difference of 0.7 degrees Fahrenheit. Finally, using the aforementioned information, we are in the process of defining an algorithm that can be used to find the core temperature working from baseline data that will be generated during testing. We are confident in being able to improve the accuracy of this data to deliver a powerful, precise product. Dr. C. O. of the Working Dog Center, highly respected in her field, commented even unfiltered heart rate data reported within canine range, and also that the GPS tracking in particular was able to identify the location of the dog and transmit to the handler.  Any further improvements revealed as necessary by further testing will also be implemented; as previously stated, refinement of data capabilities is a major Phase II goal. Improved harness design in Phase II is also intended to improve fit, which will increase the precision of temperature readings for use in the aforementioned algorithm.