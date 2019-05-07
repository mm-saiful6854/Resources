# Resources
Important materials on different topics




Binary search: 1. https://www.geeksforgeeks.org/variants-of-binary-search/
               2. https://www.topcoder.com/community/competitive-programming/tutorials/binary-search
               
Dynamic programming: 1. https://web.archive.org/web/20180502194639/https://www.topcoder.com/community/data-science/data-science-tutorials/dynamic-programming-from-novice-to-advanced/


square root segmentation tutorials :     https://codeforces.com/blog/entry/16883

square root segmentation problem List:   1. https://codeforces.com/contest/455/problem/D
                                         2. https://codeforces.com/contest/513/problem/F2
                                         3. https://www.spoj.com/problems/RACETIME/
                                         
Counting sort : 1.https://www.geeksforgeeks.org/counting-sort/

subset generates : 1. Iteratives - CP3
                   2. Recursive  - https://www.geeksforgeeks.org/recursive-program-to-generate-power-set/
                   3. Backtracking - https://www.geeksforgeeks.org/backtracking-to-find-all-subsets/
                   
                   
                   
if A and B are double then to check A==B:
 do : if(fabs(A-B)<1e-12){
          
 }
 
 backtracking perform : n!, nCr , (p-1)(q-1)(r-1) ,subset generate : 2^n , p*q*r-1
 
 combinatories : to calculate : nCr using array : if(r>n-r) r = n-r; // knew from bacs recursion videos  , katakati done through this 
                                                                                                                line.
                                                  for(i=1;i<=r;i++) // individual multiplication can occur overflow.
                                                    {
                                                        ans*= n-r+i;
                                                        ans/=i;
                                                    }
