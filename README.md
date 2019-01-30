# Tracklytics
Swift Analytics Framework


This framework will be an end to end approach including architecture design, TDD and development that is based on the article described in https://www.swiftbysundell.com/posts/building-an-enum-based-analytics-system-in-swift and youtube channel Essentialdeveloper.com

Besides enum based approach, the architecture will evolve to protocol oriented approach where it will be more flexiable and maintainable. 


Goals :

- It needs to be easy to log events from any view controller. You should only need one line of code to log something.
- The system should support any underlying system for actually sending events to some form of backend.
- The system should be highly testable and easy to verify.
- It should be easy to add, remove & modify events and get compile time errors whenever a call site needs to be updated.



- General Architecture of Framework

![alt text](https://github.com/cagdastimurlenk/Tracklytics/blob/master/ArchitectureTracklytics.png)

- General Architecture of Usage

![alt text](https://github.com/cagdastimurlenk/Tracklytics/blob/master/ArchitectureUsage.png)
