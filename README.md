# Operating-Platforms

For the Gaming Room, I developed a comprehensive document outlining their needs and how they can best be fulfilled. The company required a server-client solution for their new Game _Draw It or Lose It_. 
The company needed to decide on an operating system to host their services, as well as which of the various configurations that platform offered that could fit their needs. 

In designing this document, I felt as though my most important contribution was the implementation of the singleton and that instance's interaction with the necessary classes. The method with which I completed this 
enables the company to host multiple games within a singular instance, enabling a scalable amount of users to partake in the same experience. 

When developing the code, I found the UML diagrams to be most beneficial, as they gave me a general layout of how best to plan the program. With the UML as a guide, I was able to first plan out the logic, then focus on implmentation
once I was satisfied with how the program could function.

In the document itself, the part I would most like to revise would be which specific version of Linux to be selected. In my original design document, I had only suggested using Linux in an umbrella term. Were I to go back, I would select
a distro of Linux that best suits a video-game server, such as Ubuntu Server. This is because while Linux is extremely configurable and therefore suitable for the task, Ubuntu Server comes with many of the necessary configuration already done,
reducing the overall workload for setup.

When considering the user's needs, I thought mostly on how, I as a developer, would like the platform to function. In this, I mean that as a developer, there are certain features and built-in configurations that make my job easier, and therefore
are more suitable to the task. Beyond the developer, though, cost is a major consideration. To the executives of the company who must make the final decision, cost plays a major role, and therefore requires heavy consideration against the ease
of development. For this reason, Linux is an excellent choice due to its extremely low cost in comparison to OSX or Windows, and has many of the features a developer would like.

When designing the software, I initially considered the basic requirements. Within that framework, I then designed a UML document to lay out the implementation. Once the UML was done, I separately created each class with its necessary functions, then
tested each class. After this, I began linking the classes as the UML required, testing each pair. After all said and done, the entire program was tested as a whole, with any bugs fixed throughout and at the end. I feel as though this is a functional
process, as attempting to write the entire program at once, then performing testing would result in more bugs than can be handled, with no real way of identifying what is causing each issue.
