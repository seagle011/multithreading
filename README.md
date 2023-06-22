# Multi-threaded Printing

This Python script demonstrates how to use threads to print numbers and letters concurrently.

#Usage

The script defines two functions, print_numbers and print_letters, which print numbers 1-10 and letters 'a'-'j' respectively. The script then creates two threads, one for each function, and starts them. The join method is called on each thread to ensure that they complete before the script exits.
