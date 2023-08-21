**#Maximum Average Subarray**
1.Initialize a variable s to keep track of the sum of the first k elements in the array.
2.Iterate through the first k elements in the array and add them to s.
3.Initialize a variable ans with the value of s.
4.Iterate from index k to the end of the array.
5.Update s by subtracting the element at index i - k and adding the element at index i.
6.Update ans by taking the maximum of its current value and s.
7.Finally, return ans / k as the maximum average value.

**
Initialize variables: cnt for vowel count.
Iterate through the first k characters in the string:
If the current character is a vowel (using the isVowel function), increment cnt.
Initialize max with the value of cnt.
Iterate from index k to the end of the string:
If the current character is a vowel, increment cnt.
If the character leaving the sliding window was a vowel, decrement cnt.
Update max with the maximum value between the current max and cnt.
Return max as the maximum count of vowels.


