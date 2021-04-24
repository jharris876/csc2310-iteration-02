#`Iteration 2: Streaming support by Jacob Harris`

##What we changed from last time:
For this second iteration we changed:

1. What type of data the program reads
2. Multiple classes and made some classes subclasses.

##Required items for a successful compile:

A couple of things you will need in order to successfully run the program is:

1. Download the latest version of  [WireShark](https://www.wireshark.org/download.html)
2. You will also need the libraries from our midterm that can be found here [GraphStream](https://graphstream-project.org/download/) and [Javafx SDK](https://gluonhq.com/products/javafx/)

After you have installed all these items we should be ready to compile Iteration 2.

##Running Iteration 2

One way you can run the program is from the command line.

**MAKE SURE YOU HAVE COMPILED ALL .JAVA FILES AND THAT THE COMPILED FILES ARE IN THE ***OUT*** THE DIRECTORY**

####To run from the command line you will use this line:

> ```java -cp %CLASSPATH% standalone.VizSharkJunior {--csv filename | --live interface }```

1. For live data from Wireshark you will use the ```--live interface``` section of the curly braces.
2. For data passed into a file you will use the ```--csv filename``` section of the curly braces.

####To run from inside of intelliJ:

To run from inside of the intelliJ terminal make sure your ***Configuration*** in the top right is set to ```standalone.VizSharkJunior```

Next you will need to specify what type of data you want to pass

1. For live data from Wireshark you will type ```--live interface``` into the program arguments part of your configuration.  

2. For data passed into a file you will type ```--csv filename``` into the program argument part of your configuration.


##Run it
After you do one of the two methods for running iteration 2. 

Press enter on the command line or press the green play button in the upper right to run

You should be able to visually see the graph and nodes connected to one another. ENJOY




