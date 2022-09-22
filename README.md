# CAR-HACKING-101
Automobiles are no longer just mechanical devices. Today’s automobiles contain a  number of different electronic components networked together that as a whole are  responsible for monitoring and controlling the state of the vehicle. Each component,  from the Anti-Lock Brake module to the Instrument Cluster to the Telematics module,  can communicate with neighboring components. Modern automobiles contain upwards  of 50 electronic control units (ECUs) networked together. The overall safety of the  vehicle relies on near real time communication between these various ECUs. While  communicating with each other, ECUs are responsible for predicting crashes, detecting  skids, performing anti-lock braking, etc. 
When electronic networked components are added to any device, questions of the 
robustness and reliability of the code running on those devices can be raised. When 
physical safety is in question, as in the case of the automobile, code reliability is even a 
more important and practical concern. In typical computing environments, like a 
desktop computer, it is possible to easily write scripts or applications to monitor and 
adjust the way the computer runs. Yet, in highly computerized automobiles, there is no 
easy way to write applications capable of monitoring or controlling the various 
embedded systems. Drivers and passengers are strictly at the mercy of the code 
running in their automobiles and, unlike when their web browser crashes or is 
compromised, the threat to their physical well-being is real. 
Some academic researchers, most notably from the University of Washington and the 
University of California San Diego [http://www.autosec.org/publications.html] have 
already shown that it is possible for code resident in some components of an 
automobile to control critical systems such as the computerized displays and locks as 
well as the automobile's braking. Furthermore, they have shown that such malicious 
code might be injected by an attacker with physical access to the vehicle or even 
remotely over Bluetooth or the telematics unit. They demonstrated that there is a real 
threat not only of accidental failure of electronic automobile systems, but there is even a 
threat of malicious actions that could affect the safety of automotive systems. However, 
their research was meant to only show the existence of such threats. They did not 
release any code or tools. In fact, they did not even reveal the model of automobile 
they studied. 
Besides discussing new attacks, this paper aims to bring accessibility to automotive 
systems to security researchers in an open and transparent way. Currently, there is no 
easy way to write custom software to monitor and interact with the ECUs in modern 
automobiles. The fact that a risk of attack exists but there is not a way for researchers 
to monitor or interact with the system is distressing. This paper is intended to provide a 
framework that will allow the construction of such tools for automotive systems and to 
demonstrate the use on two modern vehicles. This framework will allow researchers to 
demonstrate the threat to automotive systems in a concrete way as well as write 
monitoring and control applications to help alleviate this threat. 
