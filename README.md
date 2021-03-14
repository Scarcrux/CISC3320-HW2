PID Threads Design Documentation

Declare a PID thread class that initializes a thread based on parameters for thread_id, thread_name and sleep duration. Import Thread from the threading class to create threads.

Within the PID thread class, define a function named run that prints when a thread begins, call the pid_cycle function, and prints when a thread ends.

Declare a function named pid_cycle that simulates the PID process: allocate a PID, sleep for a random period of time, and then release PID. This function should accept parameters for the PID value to be released and the amount of time to sleep. Indicate whether a PID is successfully allocated.

Declare a main function that acts as the command line interface for the PID thread class. Loop until the quit option is selected. Handle non-integer input and invalid menu choices. If the user wants to allocate PID threads, then attempt to initialize a PID map.

Get user input for PID threads to create. For each thread, call it with a randomly generated value for the sleep parameter. Set the final PidThread to finish last so that the menu follows completion of all threads.
