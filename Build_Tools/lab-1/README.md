git clone the repo 

i test  to make sure the units is work well   wwith command mvn test 


build the app  with command mvn package  




#####screnshots#####
osa@osama:~/ivolve_tasks/Build_Tools/lab-1$ tree
.
├── pom.xml
├── src
│   ├── main
│   │   └── java
│   │       └── com
│   │           └── example
│   │               └── calculator
│   │                   ├── Calculator.java
│   │                   └── Main.java
│   └── test
│       └── java
│           └── com
│               └── example
│                   └── calculator
│                       └── CalculatorTest.java
└── target
    ├── calculator.jar
    ├── classes
    │   └── com
    │       └── example
    │           └── calculator
    │               ├── Calculator.class
    │               └── Main.class
    ├── generated-sources
    │   └── annotations
    ├── generated-test-sources
    │   └── test-annotations
    ├── maven-archiver
    │   └── pom.properties
    ├── maven-status
    │   └── maven-compiler-plugin
    │       ├── compile
    │       │   └── default-compile
    │       │       ├── createdFiles.lst
    │       │       └── inputFiles.lst
    │       └── testCompile
    │           └── default-testCompile
    │               ├── createdFiles.lst
    │               └── inputFiles.lst
    ├── surefire-reports
    │   ├── com.example.calculator.CalculatorTest.txt
    │   └── TEST-com.example.calculator.CalculatorTest.xml
    └── test-classes
        └── com
            └── example
                └── calculator
                    └── CalculatorTest.class

33 directories, 15 files
