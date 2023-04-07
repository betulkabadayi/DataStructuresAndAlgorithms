# Binary Search Tree Project

**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]** 

 - 7 is the root.
 - 5<7 so 5 will be placed left of the root.
 - 1<7 and 1<5 so 1 will be placed left of the 5.
 - 8>7 so it will be placed right of the root.
 - 3<7, 3<5 and 3>1 so 3 will be placed right of the 1.
 - 6<7, and 6>5 so 6 will be placed right of the 5.
 - 0<7,0<5,0<1 so it will be placed left of the 1.
 - 9>7, 9>8 so it will be placed right of the 8.
 - 4<7,4<5,4>1, 4>3 so 4 will be placed right of the 3.
 - 2<7,2<5,2>1, 2<3 so 2 will be placed left of the 3.

```
         7  
       /   \  
      5     8
     / \     \  
    1   6     9   
   / \   
  0   3  
     / \      
    2   4       
```

