**Configuring Scala Examples for Intellij**

Example: DITA (https://github.com/TsinghuaDatabaseGroup/DITA)

First, we must configure the Scala application.

1. In IntelliJ, choose menu Run -> Edit Configurations... 
![alt text](../img/Configure1.png "Run -> Edit Configuration")
2. Click the button (+) in the upper left of the window. Then, pick Application.
![alt text](../img/Configure3.png "Adding new Application Configuration")
2. Then, fill out the class name (Example: I am using the DITAIndexExample), the Working directory, and the classpath. Make sure that the 'Include dependencies with "Provided" scope' is checked. Then, click OK.
![alt text](../img/Configure2.png "Configuring the applicatoin")

After that, we can nicely run the code and waiting for the results by choosing the menu Run -> Run 'DITAIndexExample'. The execution will run on the console as depicted below.
![alt text](../img/Run1.JPG "Run the Scala Application")


