# shms-web-ui

SHMS Web UI is an angular 5 project

# Run instructions
Pre-requisites
Make sure the following software/packages are installed on machine,
Install Java 8(JDK 1.8.x)(for server)
-	Download required version of java from official website and install
Install Node.js(>=8.10)(for client)
-	Download compatible version of node for your platform(i.e. Windows, Linux) and install
Install Yarn(1.6.0)(for client)
-	Download yarn package manager and install after node installation

# To run a server:
Add java jdk installation path into JAVA_HOME environment variable. Ignore its already done.
Open the terminal and cd to exact path and issue the following command

For windows
`cmd> mvnw`

For linux/mac
`cmd> ./mvnw`

It will start the server at http://localhost:8080

# To run a client:
Same way open the terminal and change to exact directory path and issue the following command

`cmd> yarn install`

it take while. Once its done follow the next step

`cmd> yarn start`

This will start the client UI at http://localhost:9000
Note: Its initial project structure, we will be adding shms ui layouts and client modules into it.  Now we are ready work on this and later we will integrate the changes into final code base.
