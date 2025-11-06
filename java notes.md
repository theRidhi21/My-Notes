##for (char c : s.toCharArray()) {
            freq[c - 'a']++;##
These lines will do the following changes:
>Converts the string s into a char[] and iterates over each character c. This is a concise for-each loop.
>Maps the character c to an index: 'a' → 0, 'b' → 1, ..., 'z' → 25. Then increments the frequency for that letter. (Assumes input is lowercase a–z.)
            
