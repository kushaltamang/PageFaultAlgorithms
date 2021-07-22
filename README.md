A page fault is a type of exception raised by computer hardware when a running program accesses a memory page that is not currently mapped by the memory management unit into the virtual address space of a process. These fault pages needs to be replaced using page-replacement algorithms: FIFO, Optimal, MFU, and LRU.

This is a program that implements the FIFO, Optimal, MFU, and LRU page-replacement algorithms. Given a page-reference string, where page numbers range from 0 to 9, it applies the page-reference string to each algorithm, and output the number of page faultsincurred by each algorithm.

Compiling Instructions:
- ./a.out <filename>
 
 Example:
- ./a.out test1.txt 
