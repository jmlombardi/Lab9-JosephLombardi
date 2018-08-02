## Joseph Lombardi
### COMP 271
### Lab 9
#### Due 08/01/2018


### Questions

##### Try using a TreeMap and a HashMap instead of MyHashMap.
##### a. Are the resulting word frequencies any different?
    
I was not able to build my program using gradlew build.  Although the results should be the same.

##### b. Is the time performance any different? If so, how would you rank the three implementations (in increasing order of time complexity)?
    
I was not able to build my program using gradlew build.


##### How are % and Math.floorMod different? Which works more reliably for computing a hash table index?
    
Using the % could give you a negative index which we want to avoid.  Math.floorMod works more reliably.

##### What is the time complexity of MyHashMap.size(), and how could you make it much more efficient?
    
The time complexity of MyHashMap.size() is O(n) because the larger our arraylist is the more buckets we have to loop through.
   
##### How does this implementation compare to one where you would directly use your linked Node class from the earlier assignment? Answer briefly in terms of ease of implementation, correctness, reliability, and performance.
    
This implementation is more complex as we are writing our own methods but the reliability and the performance should be about the same.  Java's Hashmap calculaties their hashcode a bit different.