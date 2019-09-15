# Backtracking-algorithms
STATEMENT:
To implement 16-puzzle program using Backtracking
EXPLANATION:
Backtracking is an algorithm technique for solving problem recursively by trying to build a solution incrementally,one piece at a time removing those solutions that fail to satisfy the constraints of the problem at any point of time(by time, here, is referred to the time elapsed till reaching any search tree).
ALGORITHM:
step 1:a)Start in the left most column
            b)If all the queens are placed return tree
            c)Try all rows in the current column Do following for     
             every tired row.
step 2:a)If the queen can be placed safely in this row then 
           mark .This as part of the solution and recursively  check 
           if placing queen here leads to a solution.
           b)If placing the queen in leads to a solution then return    
           true.
           c)If placing queen doesn't lead to a solution then
        unmark this and go to step(a) to try other rows.
step 3:If all rows have been tried and nothing worked,return 
           falls to trigger backtracking.
