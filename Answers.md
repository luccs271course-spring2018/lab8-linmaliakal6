# Answers to Questions
- Why does `FixedArrayQueue` require an explicit constructor?  
This class requires an explicit contructor because its specific elements like the size and 
capacity it has need to be defined.
- What happens when you offer an item to a full `FixedArrayQueue`?  
If an item is offered to a full queue, then that part would return false because there
is no room for the new item. 
- What happens when you poll an empty `FixedArrayQueue`?  
If you poll an empty queue, that method would return null because there is nothing inside
of the queue to be removed.
- What is the time and (extra) space complexity of each of the `FixedArrayQueue` methods?  
For offer, it would be O(1).   
For peek, it would be O(1).  
For poll, it would be O(1).
For size, it would be O(1).  
For isEmpty, it would be O(1).  
For asList, it would be O(n).