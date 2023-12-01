**#Maximum Average Subarray**
1.Initialize a variable s to keep track of the sum of the first k elements in the array.
2.Iterate through the first k elements in the array and add them to s.
3.Initialize a variable ans with the value of s.
4.Iterate from index k to the end of the array.
5.Update s by subtracting the element at index i - k and adding the element at index i.
6.Update ans by taking the maximum of its current value and s.
7.Finally, return ans / k as the maximum average value.


**#Maximum number of vowels in a substring**
1.Initialize variables: cnt for vowel count.
2.Iterate through the first k characters in the string:
3.If the current character is a vowel (using the isVowel function), increment cnt.
4.Initialize max with the value of cnt.
5.Iterate from index k to the end of the string:
6.If the current character is a vowel, increment cnt.
7.If the character leaving the sliding window was a vowel, decrement cnt.
8.Update max with the maximum value between the current max and cnt.
9.Return max as the maximum count of vowels.


