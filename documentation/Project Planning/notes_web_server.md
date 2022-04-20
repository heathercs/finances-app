# Web Server Notes

## Basics

* computer where web content stored
    * host websites, storage, etc.
* receives request, communicates with db, sends file to client, 
* architecture
    * concurret approach
        * multiple requests at a time
        * multi-processing, parent process creates children, distributes requests to children
        * multi-threaded, multiple single threaded processes
        * hybrid approach combines multi-processsing, multi-threaded; multiple processes create multiple child threads, each thread handles one connection
    * Single-process-event-driven approach
* Common web servers
    * Apache HTTP Server
        * popular, open-source, wide compatibility
    * Internet Information Services (IIS)
        * Microsoft, high-performance
    * Lighttpd
        * open-source, FreeBSD OS, also other common OSs
    * Sun Java System Web Server
        * free, proprietary, medium-large web sites
    * Jigsaw Server
        * open-source, W3C Server
* languages
    * Scriptint
        * JavaScript (Node.js)
            * popular, extensible
        * Ruby (Ruby on Rails)
            * extensible
            * Good testing
            * reliable, fast
            * slow runtime
            * new language
            * difficult debugging
        * PHP
            * popular, dwindling
            * open-source
            * good security, community
            * limitations compared to modern
        * Python
            * many libraries
            * embeddable code
            * difficult database integration
            * require extensive testing, debugging
        * Java
            * scalable
            * multi-thread support
            * open-source libraries
            * good security
            * time consuming
            * expensive back-end
            * limitations compared to modern
        * Perl
            * open-source
            * extensible, can be run by C & C++
            * limitations compared to modern
        * C#
        * C++ 
        * Scala
    * Database
    * Frameworks
        * .Net
            * open-source, Microsoft
            * software framework, virtual machine for other languages
            * for developing form-based applications



    * MongoDB
    * Redis

* REST API
    * Representational State Transfer
    * web service architectural style
        * client software accesses
        * server uses API to provide access
        * resource from server to client

* MVC (Model View Controller) pattern
    * Model
        * backend, data logic
    * View
        * frontend, GUI
    * Controller
        * controls how data displayed
    


## References

* Web server Basics
    * https://www.tutorialspoint.com/internet_technologies/web_servers.htm
* .Net
    * https://www.geeksforgeeks.org/introduction-to-net-framework/ 
* REST API
    * https://www.altexsoft.com/blog/rest-api-design/