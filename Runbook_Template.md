
##Service or System Overview##

***Service or system name:** 

###Business overview##

> What need is met by this service or system? What expectations do we have about availability and performance?

###Technical overview###

> What kind of system is this? Web-connected order processing?  Internal HTTP-based API? Ports for communicating?


###Service owner###

> Which team owns and runs this service or system?


###Dependencies###

> What all Software applications, daemons, services, etc. are there on which this system/service is dependent on?


##System/Service Characteristics##

###Required resources (If Any)###

> What compute, storage, database, metrics, logging, and scaling resources are needed? What are the minimum and expected maximum sizes (in CPU cores, RAM, GB disk space, GBit/sec, etc.)?

###Connectivity design###

> How and where does data flow through the system? What controls or triggers data flows?

###User Access###
>Which users/group has the access? Does it require root access? 

###System/Service configuration###

>How to configure it? Any configuration management tool used to do that?

###Start/Stop
> How to start, stop, disable, check status of the system/service

###Fault Tolerance and High Availability###

> How is the system resilient to failure? What mechanisms for tolerating faults are implemented? How is the system/service made highly available?



##System backup and restore##

###Backup requirements###

> Which parts of the system need to be backed up

###Backup procedures###

> How does backup happen? Is service affected? Should the system be [partially] shut down first?

###Restore procedures###

> How does restore happen? Is service affected? Should the system be [partially] shut down first?

##Monitoring and alerting##

###Log aggregation solution###

> What log aggregation & search solution will be used?

###Events and error messages###

> What significant events, state transitions and error events may be logged?


###Health checks###

> How does the system report its own health?



##Maintenance tasks##
###Patching###

> How should patches be deployed and tested?

###Uninstall
> How to uninstall?
