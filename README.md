## Requirements
* java7 or more tested by 1.7.0_02
* gradle 1.0-rc-3 (for development and build)
* eclipse 3.7.2 (for development)
    * [Groovy-Eclipse 2.6.1](http://groovy.codehaus.org/Eclipse+Plugin)

## Setup for development
* clone this repository  
  `git clone git@github.com:taichi/jetty8-websocket-example.git`  
* make gradle.properties
    * add proxy entry if you need.
* if you haven't use gradle yet
    * execute gradle installation shell script called gradle wrapper.  
    `gradlew` (Linux/Mac)  
    `gradlew.bat` (Windows)  
* convert to eclipse project  
  `gradlew eclipse`  
* run test  
  `gradlew test`


## License
Apache License, Version 2.0

