<!--

       ___              _   _                                        
      / __|_ _ ___ __ _| |_(_)_ _  __ _                              
     | (__| '_/ -_) _` |  _| | ' \/ _` |                             
      \___|_| \___\__,_|\__|_|_||_\__, |                             
     |  \/  |_  _| | |_(_)___| _ \|___/__  __ ___ ______             
     | |\/| | || | |  _| |___|  _/ '_/ _ \/ _/ -_|_-<_-<             
     |_|  |_|\_,_|_|\__|_|   |_| |_| \___/\__\___/__/__/             
     |  \/  |__ _ __    /_\  _ __ _ __| (_)__ __ _| |_(_)___ _ _  ___
     | |\/| / _` / _|  / _ \| '_ \ '_ \ | / _/ _` |  _| / _ \ ' \(_-<
     |_|  |_\__,_\__| /_/ \_\ .__/ .__/_|_\__\__,_|\__|_\___/_||_/__/
                            |_|  |_|                                 

                   by Christian Tietze, 2015

-->

Creating Multi-Process Mac Applications
=======================================

This is the book manuscript for "[Creating Multi-Process Mac Applications][leanpub]".

[leanpub]: https://leanpub.com/create-multi-process-mac-apps

Outline
-------

* Part 1: Understanding the problem
    * Inter-Process Communication on the Mac
    * How popular app developers solve the problem
* Part 2: Solving the problem
    * Preparing the Architecture
        - A bit of Domain-driven Design Vocabulary Recap
        - Bounded Contexts
        - Aggregates
        - Rephrasing the problem: integrating Bounded Contexts
        - Sharing Data and Eventual Consistency
    * Organizing the database
        - Benefits and Drawbacks of Sharing a Core Data Store
        - Benefits and Drawbacks of Using Different Storage Mechanisms
    * Implementing the Processes
        - Bootstrapping a Multi-Process Xcode Project
        - Test-Driving the XPC API
        - Testing XPC Calls: Define Adapters
* Part 3: Discussion
* Appendix
    * Including interesting links, books, etc.

License
=======

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Develop Mac Apps With a Clean Architecture and Swift</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://christiantietze.de/mac-appdev-book" property="cc:attributionName" rel="cc:attributionURL">Christian Tietze</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution 4.0 International License</a>.


