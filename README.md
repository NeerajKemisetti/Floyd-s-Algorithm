# Floyd-s-Algorithm
Also know as Tortoise and the hare problem. 
We can find out if a linked list is looped by running two pointers, fast and slow.
The slow pointer moves one node at a time starting from the head node.
The fast pointer skips a node and moves twice as fast as the slow pointer.
If the list is looped, the fast pointer doesn't reach NULL, the slow pointer catches up to it and at some point, they both will meet at a node.
If the list is not looped then the fast pointer reaches NULL at O(N/2) time.
The time complexity is O(N) cause only one traversal of the loop is needed.
Space complexity is O(1) as no extra space is required.
