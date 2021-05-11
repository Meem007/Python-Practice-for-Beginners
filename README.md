# Python-Practice-for-Beginners
Basically this project help to learn python program for newcomer. Python program uses in myriad field such as- developing complex scientific numeric and web applications, data analysis and visualization. 


<h2 id="index"> Warmup-1  | <a href="#warmup_2">Warmup-2</a> | <a href="#string_1">String-1</a> </h2>

<hr>
<h2> Warmup-1</h2>

<h3> Exercise 1: Sleep </h3> 

The parameter weekday is true if it is a weekday, and the parameter vacation is true if we are on vacation. We sleep in if it is not a weekday or we're on vacation. Return true if we sleep in.


sleep_in(false, false) → true <br>
sleep_in(true, false) → false <br>
sleep_n(false, true) → true 

<a href='https://github.com/Meem007/Python-Practice-for-Beginners/blob/main/solutions/Exercise_N_01.ipynb'>solution</a>



<h3> Exercise 2: Monkey Trouble </h3> 

We have two monkeys, a and b, and the parameters a_smile and b_smile indicate if each is smiling. We are in trouble if they are both smiling or if neither of them is smiling. Return True if we are in trouble.


monkey_trouble(True, True) → True <br>
monkey_trouble(False, False) → True <br>
monkey_trouble(True, False) → False

<a target="_blank" href='https://github.com/Meem007/Python-Practice-for-Beginners/blob/main/solutions/Exercise_N_02.ipynb'>solution</a>


<h3> Exercise 3: Sum Double </h3>

Given two int values, return their sum. If the two values are the same, then return double their sum.


sum_double(1, 2) → 3 <br>
sum_double(3, 2) → 5 <br>
sum_double(2, 2) → 8 

<a target="_blank" href='https://github.com/Meem007/Python-Practice-for-Beginners/blob/main/solutions/Exercise_N_03.ipynb'>solution</a>


<h3> Exercise 4: Absolute Difference</h3>


Given an int n, return the absolute difference between n and 21, except return double the absolute difference if n is over 21.


diff21(19) → 2 <br>
diff21(10) → 11 <br>
diff21(21) → 0

<a target="_blank" href='https://github.com/Meem007/Python-Practice-for-Beginners/blob/main/solutions/Exercise_N_04.ipynb'>solution</a>


<h3> Exercise 5: Parrot Trouble</h3>

We have a loud talking parrot. The "hour" parameter is the current hour time in the range 0..23. We are in trouble if the parrot is talking and the hour is before 7 or after 20. Return True if we are in trouble.

parrot_trouble(True, 6) → True <br>
parrot_trouble(True, 7) → False <br>
parrot_trouble(False, 6) → False


def parrot_trouble(talking, hour):
  
  

  return asnwer

<a target="_blank" href='https://github.com/Meem007/Python-Practice-for-Beginners/blob/main/solutions/Exercise_N_05.ipynb'>solution</a>


<h3> Exercise 6: Return Sum </h3>

Given 2 ints, a and b, return True if one if them is 10 or if their sum is 10.


makes10(9, 10) → True <br>
makes10(9, 9) → False <br>
makes10(1, 9) → True

<a target="_blank" href='https://github.com/Meem007/Python-Practice-for-Beginners/blob/main/solutions/Exercise_N_06.ipynb'>solution</a>


<h3> Exercise 7: Absolute Hundred </h3>

Given an int n, return True if it is within 10 of 100 or 200. Note: abs(num) computes the absolute value of a number.


near_hundred(93) → True <br>
near_hundred(90) → True <br>
near_hundred(89) → False 

<a target="_blank" href='https://github.com/Meem007/Python-Practice-for-Beginners/blob/main/solutions/Exercise_N_07.ipynb'>solution</a>

<h3> Exercise 8: Positive Negative </h3>

Given 2 int values, return True if one is negative and one is positive. Except if the parameter "negative" is True, then return True only if both are negative.


pos_neg(1, -1, False) → True <br>
pos_neg(-1, 1, False) → True <br>
pos_neg(-4, -5, True) → True

<a target="_blank" href='https://github.com/Meem007/Python-Practice-for-Beginners/blob/main/solutions/Exercise_N_08.ipynb'>solution</a>


<h3> Exercise 9: Not String </h3>

Given a string, return a new string where "not " has been added to the front. However, if the string already begins with "not", return the string unchanged.


not_string('candy') → 'not candy' <br>
not_string('x') → 'not x' <br>
not_string('not bad') → 'not bad'

<a target="_blank" href='https://github.com/Meem007/Python-Practice-for-Beginners/blob/main/solutions/Exercise_N_09.ipynb'>solution</a>


<h3> Exercise 10: Missing Character </h3>

Given a non-empty string and an int n, return a new string where the char at index n has been removed. The value of n will be a valid index of a char in the original string (i.e. n will be in the range 0..len(str)-1 inclusive).


missing_char('kitten', 1) → 'ktten'
missing_char('kitten', 0) → 'itten'
missing_char('kitten', 4) → 'kittn'

<a target="_blank" href='https://github.com/Meem007/Python-Practice-for-Beginners/blob/main/solutions/Exercise_N_10.ipynb'>solution</a>


<h3> Exercise 11: Front Back String </h3>

Given a string, return a new string where the first and last chars have been exchanged.

front_back('code') → 'eodc' <br>
front_back('a') → 'a' <br>
front_back('ab') → 'ba'

<a target="_blank" href='https://github.com/Meem007/Python-Practice-for-Beginners/blob/main/solutions/Exercise_N_11.ipynb'>solution</a>

<h3> Exercise 12: Front String </h3>

Given a string, we'll say that the front is the first 3 chars of the string. If the string length is less than 3, the front is whatever is there. Return a new string which is 3 copies of the front.


front3('Java') → 'JavJavJav' <br>
front3('Chocolate') → 'ChoChoCho'<br>
front3('abc') → 'abcabcabc'

<a target="_blank" href='https://github.com/Meem007/Python-Practice-for-Beginners/blob/main/solutions/Exercise_N_12.ipynb'>solution</a>

<hr>

<h2 id="warmup_2"> Warmup-2</h2>

<h3> Exercise 13: String Times </h3>


Given a string and a non-negative int n, return a larger string that is n copies of the original string.


string_times("Hi", 2) → "HiHi" <br>
string_times("Hi", 3) → "HiHiHi"<br>
string_times("Hi", 1) → "Hi"

<a target="_blank" href='https://github.com/Meem007/Python-Practice-for-Beginners/blob/main/solutions/Exercise_N_13.ipynb'>solution</a>


<h3> Exercise 14: Front Time </h3>

Given a string and a non-negative int n, we'll say that the front of the string is the first 3 chars, or whatever is there if the string is less than length 3. Return n copies of the front;


front_times('Chocolate', 2) → 'ChoCho' <br>
front_times('Chocolate', 3) → 'ChoChoCho'<br>
front_times('Abc', 3) → 'AbcAbcAbc'

<a target="_blank" href='https://github.com/Meem007/Python-Practice-for-Beginners/blob/main/solutions/Exercise_N_14.ipynb'>solution</a>

<h3> Exercise 15: String Bits</h3>

Given a string, return a new string made of every other char starting with the first, so "Hello" yields "Hlo".

string_bits('Hello') → 'Hlo'<br>
string_bits('Hi') → 'H' <br>
string_bits('Heeololeo') → 'Hello'

<a target="_blank" href='https://github.com/Meem007/Python-Practice-for-Beginners/blob/main/solutions/Exercise_N_15.ipynb'>solution</a>

<h3> Exercise 16: String Splosion</h3>

Given a non-empty string like "Code" return a string like "CCoCodCode".

string_splosion('Code') → 'CCoCodCode'<br>
string_splosion('abc') → 'aababc'<br>
string_splosion('ab') → 'aab'

<a target="_blank" href='https://github.com/Meem007/Python-Practice-for-Beginners/blob/main/solutions/Exercise_N_16.ipynb'>solution</a>

<h3> Exercise 17: String Number</h3>

Given a string, return the count of the number of times that a substring length 2 appears in the string and also as the last 2 chars of the string, so "hixxxhi" yields 1 (we won't count the end substring).


last2('hixxhi') → 1<br>
last2('xaxxaxaxx') → 1<br>
last2('axxxaaxx') → 2

<a target="_blank" href='https://github.com/Meem007/Python-Practice-for-Beginners/blob/main/solutions/Exercise_N_17.ipynb'>solution</a>

<h3> Exercise 18: Array Counting</h3>

Given an array of ints, return the number of 9's in the array.

array_count9([1, 2, 9]) → 1<br>
array_count9([1, 9, 9]) → 2<br>
array_count9([1, 9, 9, 3, 9]) → 3

<a target="_blank" href='https://github.com/Meem007/Python-Practice-for-Beginners/blob/main/solutions/Exercise_N_18.ipynb'>solution</a>

<h3> Exercise 19: Array Length</h3>

Given an array of ints, return True if one of the first 4 elements in the array is a 9. The array length may be less than 4.


array_front9([1, 2, 9, 3, 4]) → True<br>
array_front9([1, 2, 3, 4, 9]) → False<br>
array_front9([1, 2, 3, 4, 5]) → False

<a target="_blank" href='https://github.com/Meem007/Python-Practice-for-Beginners/blob/main/solutions/Exercise_N_19.ipynb'>solution</a>

<h3> Exercise 20: Array Number</h3>

Given an array of ints, return True if the sequence of numbers 1, 2, 3 appears in the array somewhere.


array123([1, 1, 2, 3, 1]) → True<br>
array123([1, 1, 2, 4, 1]) → False<br>
array123([1, 1, 2, 1, 2, 3]) → True

<a target="_blank" href='https://github.com/Meem007/Python-Practice-for-Beginners/blob/main/solutions/Exercise_N_20.ipynb'>solution</a>

<h3> Exercise 21: String Matching</h3>

Given 2 strings, a and b, return the number of the positions where they contain the same length 2 substring. So "xxcaazz" and "xxbaaz" yields 3, since the "xx", "aa", and "az" substrings appear in the same place in both strings.


string_match('xxcaazz', 'xxbaaz') → 3<br>
string_match('abc', 'abc') → 2<br>
string_match('abc', 'axc') → 0

<a target="_blank" href='https://github.com/Meem007/Python-Practice-for-Beginners/blob/main/solutions/Exercise_N_21.ipynb'>solution</a>


<a href="#index">Back to Index</a>
<hr>



<h2 id="string_1"> String-1</h2>


<a href="#index">Back to Index</a>

<hr>
