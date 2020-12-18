Process Instance from process and it's Life cycle
=================================================

This exmaple provides inforamtion about, how to create dynamic process instance from the process.

In this example we are using sub-process start the other processes dynamically.

Post deploying the kJar follow the the below steps.

* Step 1: Create a process instance for [parent-process]()
* Step 2: Signal created process instance with signal name and dyncamic process id as data to signal
![project modules1](images/Signal1.png)
* Step 3: Now observe the newly created process instance.
![project modules2](images/Pi1.png)
* Step 4: Repeat the step 2 for all other processes.
![project modules3](images/Signal3.png)
![project modules4](images/Pi2.png)
