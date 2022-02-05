# rmicalculator
Java RMI Service
Setup a calculator service using Java RMI.

Before running any services, it is imperative to initiate the rmiregistry command inside the source directory containing the CalculatorServer java file.
Server was run locally (Instanciated a server by running the main() in CalculatorServer.java).
When client is run, it connects to localhost on port 1099 (default for rmiregistry) and then uses the service provided by the server. 
The results are displayed in the command line.
