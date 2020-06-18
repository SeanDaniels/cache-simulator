* Purpose
  - Simulate a memory cache
* Description
  - A trace file, which is essentially a text file containing addresses and operations, is loaded into the program. That trace file is  used as instructions to populate a data array simulating a cache. Using the instructions provided in the trace file, the program returns  statistics relative the simulated cache's memory access.
* Testing
  - Multiple testfiles are located in the 'testcase' directory. These testcases are small snippets which instantiate a particular cache   configuration.
* How do I know these are correct?
  - I solved the memory accesses by hand for the first 3 test cases. After those, I was satisfied that the logic of my program was correct
* To Run
  - Some C++ compiler, I used g++.
  - Using a terminal or command prompt, navigate to the this folder ('cache-simulator).
  - Once in 'cache-simulator' folder, type './run'
  - The 'output' folder should now contain 5 .txt files, one for each test case
  - To run again, type 'make clean'. This deletes the files associated with the last run. Repeating the ./run command will execute the 5  test cases again.
