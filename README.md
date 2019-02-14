# Week1day3

**************  Homework Week 1 Day 3  *************************
Answer the following questions:
1.  What are the major components in android?
    • Linux Kernel
    • Hardware Abstraction Layer
    • Android Runtime
    • Native C/C++ Libraries
    • Java API Framework
    • System Apps
2.  What are all the activity lifecycles and explain what each details?
	Activity lifecycles simply defines the different states of the user navigation, through, out of and back, has the activity instances transition. 
    • onCreate(): It boots up the first instance of the system when the activity is created and create every necessary instantiation. With quick completion it calls the onStart() method.
    • onStart(): It makes the activity visible to the user, it initializes the code and maintains the UI. Same as onCreate(), it finishes quickly and calls the onResume() method.
    • onResume(): This is the user interaction state, the app stays on this state until there is some utercation where focus is taken away from the app ,(eg. receiving a phone call). It only calls another lifecycle method like onPause() when there is an event interruption.
    • OnPause(): when there is an indication that the user is leaving the activity, this method is called. It means the activity is no longer in the foreground.
    • OnStop(): when the activity is no longer visible to the user, this method is called. Another instance would be when the activity has finished running, and is about to be terminated.
    • OnDestroy(): This method is called on two instances, where the activity is finishing and the system is temporarily destroying due to a configuration change.
3.  Explain each step of the sprint in agile.
	Sprint refers to a set period of time during which a certain task or activity is completed and then reviewed.
    • Section planning – Just like the name implies 
    • There is the stand up – Retrospective section
4.  What is dalvik and ART?
	ART is the android runtime, that manages the runtimes used by applications on some system services on android. While dalvik is the actual virtual machine that android runs its apps on.
5.  How is the android platform architecture designed?
	The based way to say it is Layered (Like surface on surface).
