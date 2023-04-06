#  Selection Sort Project

**[22,27,16,2,18,6]** 

*Since there are n unsorted elements there will be (n-1) comparisons.*
**First Step:**  Comparing 22 with others and swap 2 and 22 -> [**2**,27,16,22,18,6]

*Since there are (n-1) unsorted elements there will be (n-2) comparisons.*
**Second Step:** Comparing 27 with others and swap 6 and 27 -> [**2,6**,16,22,18,27]


*Since there are (n-2) unsorted elements there will be (n-3) comparisons.*
**Third Step:** Comparing 16 with others and don't change anything since 16 is smaller than other unsorted items. -> [**2,6,16**,22,18,27]

*Since there are (n-3) unsorted elements there will be (n-4) comparisons.*
**Fourth Step:** Comparing 22 with others and swap 22 and 18 -> [**2,6,16,18**,22,27]

*Since these are the last two unsorted elements of array there will be 1 comparison.*
**Fifth Step:** Comparing 22 with 27 and don't change anything since 22 is smaller than 27 -> [**2,6,16,18,22**,27]

Final sorted array is [2, 6 ,16 ,18 ,22 ,27]

----------
Complexity Level: (n-1)+(n-2)+(n-3)+(n-4)+1 = n*(n-1)/2 -> O(n^2)

----------

In the final sorted array '18' is in the middle. So 18 is a **average case.**

---------
First Four Steps Of Selection Sort For [7,3,5,8,2,9,4,15,6]:

**1** [**2**,3,5,8,7,9,4,15,6]  
**2** [**2,3**,5,8,7,9,4,15,6]  
**3** [**2,3,4**,8,7,9,5,15,6]  
**4** [**2,3,4,5**,7,9,8,15,6]
