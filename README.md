# Security-and-Automation-System

When any person enters the library/study room or any other place where this system is being 
preinstalled, then he/she will have to write their respective PRN in the register to mark their presence. If 
some students don’t write their PRN in the registers, then their record will not be validated. 
 Hence to maintain security of the place, and at the same time, to maintain a record of count of 
members entering the place, this system has been designed. 
 All the students have their own ID card issued by the college. So the Barcode Scanner will scan the 
barcode which is there on the Student’s ID, if the ID Scanned is present in the Database, then only the 
student will be allowed to enter the room, otherwise, a buzzer will be sounded, alerting the security 
guards of an invalid person entering the room. For project perspective, following is the list of PRNs 
which are valid, while the rest being scanned by the barcode will be treated as invalid.
When students enter the room, then in that case, the IR Sensor Entry Detector will detect it and 
will pass the count information to the Arduino Board. Hence based on the count, the LEDs will be turned 
ON. As the number of students in the room increases/decreases, at that time, the count will be 
automatically changed (increased/decreased). 
When any student leaves the room, then in that case, the IR Sensor Exit Detector will detect the 
student and count will be decreased. When count is exactly equal to 0, means at that time, no one is 
present in the room. Hence at this stage, all the LEDs will be automatically turned OFF.
In this way, we are able to save power and make effective use of electricity and allow the authority 
or any other concerned members, access to the count of students present in the room. Also, we are able to 
give security to the students as well, since students with valid identification will only be able to enter into 
the room. 
