PURPOSE
=======
Demonstrate some features of the ZCMD framework by providing a sample 
"zcmd stack" of containers.

CONVENTIONS
===========
The "zcmd stack" of containers is defined and managed in the **"stack" folder**.

 * stack/stack.env <-- This is where we define our stack environment values.
 * stack/docker-compose.yml <-- This where we define the services of our stack.
 * stack/custom <-- By convention, we place DEV, STAGE, PROD specific confguration files into this folder.
 
The runtime content of our stack services is maintained in the **"runtime-shared-files" folder**.

AVAILABLE SERVICES IN THIS DEMO STACK
=====================================
Apache Webserver Demonstration Page
 * localhost:11080

Phpmyadmin -- A database management program
 * localhost:18080
 * Documentation available at https://github.com/phpmyadmin

Adminer -- A database management program like phpmyadmin 
 * localhost:18888
 * Documentation available at https://docs.docker.com/samples/library/adminer/
