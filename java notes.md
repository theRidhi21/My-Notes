#### for (char c : s.toCharArray()) 
             freq[c - 'a']++;
It is an in-built function available in java.These lines will do the following changes:
> Converts the string s into a char[] and iterates over each character c. This is a concise for-each loop.
> Maps the character c to an index: 'a' → 0, 'b' → 1, ..., 'z' → 25. Then increments the frequency for that letter. (Assumes input is lowercase a–z.).
            


#### int minEven = Integer.MAX_VALUE;
Initializes minEven to the largest possible int value so the first even frequency encountered will replace it. This helps find the minimum even count.



#### for (int count : freq) 
Iterates over each frequency value stored in the freq array.
#### NOTE :- ':' is used for counting as along as we know the start and end variable and need not to know the no. of iterations.
