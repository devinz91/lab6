1. Queue needs to have a constructor because we need to specify the capacity. 
2. The array would already be full so you get false in return.
3. When you poll an empty FixedArrayQueue, the result would be null. 
4. All have a time and space of O(1) except for asList which would be O(n).  