# Phone-Home

Phone Home

Description

When relay towers for mobile telephones communicate with the mobile phones in their area, there is always the possibility of interference. So, when assigning the transmission frequency, the FCC makes sure that nearby towers have frequencies that aren't too close. On the other hand, the FCC does not want to assign too many different frequencies; they want to save as many as possible for other uses. 
Your job is to find an optimal assignment of frequencies. 
In this problem, the frequencies will be integers. Nearby towers must be assigned frequencies that differ by at least 2. You'll find an assignment using as few frequencies as possible. For example, consider the following two arrangements of towers. Two towers near each other are indicated by the connecting line. 

Note that the following are legal frequency assignments to these two tower configurations. However,the second arrangement does not use the fewest number of frequencies possible, since the tower with frequency 5 could have frequency 1. 

Input

There will be multiple test cases. Input for each test case will consist of two lines: the first line will contain the integer n, indicating the number of towers. The next line will be of the form x1 y1 x2 y2 ... xn yn where xi yi are the coordinates of tower i. A pair of towers are considered "near" each other if the distance between them is no more than 20. There will be no more than 12 towers and no tower will have more than 4 towers near it. A value of n = 0 indicates end of input.

Output

For each test case, you should print one line in the format: 
The towers in case n can be covered in f frequencies. 
where you determine the value for f. The case numbers, n, will start at 1.

Sample Input

5
0 0 5 7.5 1 -3 10.75 -20.1 12.01 -22
6
0 1 19 0 38 1 38 21 19 22 0 21
0

Sample Output

The towers in case 1 can be covered in 3 frequencies.
The towers in case 2 can be covered in 2 frequencies.
