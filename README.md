# HT_CSC229Lab03
Harvey Tseng
For Lab 03 Problem 1 in CSC 229

Big O is O(n^2) --  Quadratic time complexity

See java file for additional annotations

        /*
         * Consider arr = {1, 3, 5, 8, 9} and sz = 5
         * The function works by matching each element to every other element
         * Essentially like two nested for loops
         * 
         * The while loop is n steps
         * The if block inside the while loop is n steps
         * 
         * As such: n * n + n + 1 + 1 + 1 + 1 =  n^2 + n + 4
         *                                      O(n^2)     Quadratic time complexity
         * 
         */
