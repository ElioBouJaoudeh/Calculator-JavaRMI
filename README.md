# Java RMI Calculator
Set Up a Calculator in Java RMI

## Steps to Follow:

1) Run the RMI Registry to allow remote clients to get a reference to the remote object by typing the command **rmiregistry** or **rmiregistry port** that includes the port you want to run your registry on (by default the chosen port is 1099):

![rmiregistry](https://user-images.githubusercontent.com/88712232/152417932-088e3e01-b1f5-4e4b-a139-42675bb68663.jpg)

2) Compile _CalculatorServer.java_ with the command **javac CalculatorServer.java** and then Execute the _CalculatorServer.class_ CLASS File using **java CalculatorServer** in the CLI of your working directory (where the GitHub zip folder was extracted). This will activate the Skeleton on the server side:

![CalculatorServer](https://user-images.githubusercontent.com/88712232/152418080-5c794d0e-b58d-4751-be7c-3dedbb5b6626.jpg)

3) Compile _CalculatorClient.java_ with the command **javac CalculatorClient.java** and then Execute the _CalculatorClient.class_ CLASS File using **java Calculator** in the CLI of your working directory in order to get the results of the operations entered in the main of your CalculatorClient class:

![CalculatorClient](https://user-images.githubusercontent.com/88712232/152418124-5fef85de-9b70-4b99-b19c-5a53dc87fde7.png)
