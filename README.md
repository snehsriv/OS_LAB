# OS_LAB

Question 1:
Create a scenario that has three threads. Two threads are reading the value of the shared
variable whereas third thread is incrementing the value of the shared variable. If the writer
thread is using the shared variable, no reader thread is allowed to use whereas both reader
threads can access the shared variable simultaneously. Synchronize the problem

Question 2:
Create a scenario where there are two threads where one thread is acting as a producer
thread producing a random number and the other thread is acting as a consumer thread
which printing the random number generated by producer thread. Producer thread can only
produce if the global array to place random thread is having an empty index and consumer
thread can only consume if there is element in the array. Take a shared variable counter
which counts the total no of items in the array at any time. You need to synchronize both
the threads using mutex locks for accessing the shared variable counter.

Question 3:
WAP that has three threads. Using semaphore, allow only two threads to access the shared
variable at one time

Question 4:
A parent process creates a child process. The child process after its creation will send a
message "Hello parent, this is child process" to its parent through pipe. Once the message is
received by the parent, the parent will execute and print "This is Parent process".