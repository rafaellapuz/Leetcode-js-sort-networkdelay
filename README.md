LeetCode Algorithm and Structural Foundations Assignment

912. Sort an Array
O(nlog(n)) time complexity and with the smallest space complexity possible.

Sorting an array using merge sort
I had to review lesson 7-8 graphs with this one.
Have a base case of array with length less or equal to 1
Split array into 2 (left,right)
Recursive call sort until it arrives to base case
Merge both left and right arrays


743. Network Delay Time
Return the minimum time it takes for all the n nodes to receive the signal

Using Dijkstra Algorithm with heap
I had to understand what heap/priority queue is first to fully understand how to solve it
Algorithm uses a priority queue to store the time taken to reach a node and the node itself. The algorithm starts at the starting node and adds it to the priority queue
Then enters a loop where it pops the node with the minimum time from the priority queue and marks it as visited
For each of the popped node's neighbors, the algorithm calculates the time taken to reach that neighbor and adds it to the priority queue
The algorithm continues until the priority queue is empty. The maximum time encountered during the process is the output
