# Merge Sort Project

**[16,21,11,8,12,22]** 

**First Step:**  Split array into two equal halves. -> [16,21,11] and [8,12,22]

**Second Step:** Split all elements until the atomic units of the array is reached and further division is not possible. ->
 
 [16],[21,11],[8],[12,22]

 [16],[21],[11],[8],[12],[22]

**Third Step:** Start merging the elements again based on order. ->
 [16],[11,21],[8],[12,22]

**Fourth Step:** Merge again and recreate lists with ordered elements  -> [11,16,21],[8,12,22]

**Fifth Step:** Final merge with ordered elements -> [8,11,12,16,21,22]

----------
Every merge needs (n-1) comparisons.

Deep Level: 2^x = n -> x = logn

 (n-1)*logn -> **O(nlogn)** Big-O Notation
