# DatabaseSystems-Exercise Sheet01
Slotted Page Exercise

This code implements a slotted page storage mechanism in Java, simulating a basic database page management system. The program reads TPC-H orders tuples from a file, stores them in fixed-size pages, and allows retrieval using tuple identifiers.
Features
-Implements slotted page structure with headers and tuple pointers.
-Supports storing and retrieving orders efficiently.
-Computes space utilization for pages.
-Simulates block storage via FakeBlockStorage.

Usage
-Place orders_small.tbl in the same directory as the Java file.
-Compile and run:

javac L30_SlottedPageExercise.java
java L30_SlottedPageExercise

-The program will insert all tuples, verify retrieval, and output space utilization.
