# Parallel Programming in Java  

These mini projects are programming assignments for Parallel Programming in Java offered by Rice University on Coursera, as a part of [Parallel, Concurrent, and Distributed Programming in Java Specialization](https://www.coursera.org/specializations/pcdp)

Check my repositories of [Concurrent Programming in Java](https://github.com/MaiqiDing/Concurrent-Programming-in-Java) and [Distributed Programming in Java](https://github.com/MaiqiDing/Distributed-Programming-in-Java).

## Compiling  
### Compiling with Maven

`$ mvn compile`

### Compiling with Maven using Intellij

Import project > select miniproject_ directory > Import project from external model, select Maven.

### Compiling Manually using Javac

You will need to add the following JARs to your classpath while building both the provided source and test files using javac

`$ javac -cp ./hamcrest-core-1.3.jar:./junit-4.12.jar:./pcdp-core-0.0.4-SNAPSHOT.jar:target/classes/:target/test-classes/ src/main/java/edu/coursera/parallel/Setup.java src/test/java/edu/coursera/parallel/SetupTest.java`

## Testing

### Testing with Maven

`$ mvn test`

### Testing with Maven using Intellij

Navigate to View > Tool Windows > Maven. From the Maven Projects pane, expand the Lifecycle section and double-click "test" to automatically run the tests.

### Testing Manually from Command Line

`$ java -cp ./hamcrest-core-1.3.jar:./junit-4.12.jar:./pcdp-core-0.0.4-SNAPSHOT.jar:target/classes/:target/test-classes/ org.junit.runner.JUnitCore edu.coursera.parallel.SetupTest`

## Contents

### miniproject_0

Basic Setup

### miniproject_1

Reciprocal-Array-Sum using the Java Fork/Join Framework

Used the Java Fork Join framework to write a parallel implementation of the Reciprocal Array Sum computation.

Expressed parallel algorithms by creating asynchronous tasks (async) , and waiting on collections of tasks (finish).

### miniproject_2

Analyzing Students Statistics Using Java Parallel Streams

Implemented parallel stream versions of several other imperative data analysis programs in functional way.

### miniproject_3

Parallelizing Matrix-Matrix Multiply Using Loop

Utilized PCDP's forall methods to parallelize matrix-matrix multiply.

### miniproject_4

Using Phasers to Optimize Data-Parallel Applications

Applied Java’s phasers and Java threads to the One-Dimensional Iterative Averaging algorithm.

Used fuzzy barriers and point-to-point synchronization to improve performance.

## Author

Maiqi Ding

