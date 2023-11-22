# CipherCode

You have been given a default dictionary containing cipher codes, a string representing mathematical operations to perform, an integer serving as the magic key, and a string representing the word to be encrypted.

Your task is to create a program that can encrypt and decrypt this secret word using a unique secret key. This key involves both a substitution cipher and a mathematical operation. To achieve this, you should start by comparing each character of the word with the keys in the cipher dictionary and retrieve the corresponding values. Afterward, replace the word with the retrieved values.

Following that, select a mathematical operation, such as addition or subtraction, and apply it, along with the secret key, to the ASCII values of the characters found in the cipher dictionary's values
Your program should include two functions. The first function should take a word and the generated key as inputs and encrypt the word using the substitution cipher and the chosen mathematical operation with the secret key.

By implementing these functions, you can ensure the secure encryption of the secret word, providing a robust level of secrecy and protection.

Cipher='A':'Z','B':'Y','C':'X','D':'W','E':'V','F':'U','G':'T','H':'S','I':'R','J':'Q','K':'P','L':'O','M':'N','N':'M','O':'L','P':'K','Q':'J','R':'I','S':'H','T':'G','U':'F','V':'E','W':'D','X':'C','Y':'B','Z':'A'}

Constraints:
The key is not a number it should print "Enter valid key".
The operation is not matched as addition and subtraction it should print "Invalid Operation".
If the input word is lower case it should print "Word should be in capitals".

Example -1

Input:
key = 5
Math operation = addition
word = TOSS

Output:
LQMM
Explanation:
In the chosen cipher, the ASCII value of each character is modified by adding the secret key value,
resulting in a final ASCII value for each character. This final ASCII value is then represented as 'L.' After
processing each character, the output will be a sequence of 'LQMM.'

Starting with the letter 'G,' we will replace it with 'T,' with 'T' taking the position of 'G.' Next, we will advance 5 steps forward in the alphabet, resulting in the letter 'L.' We will continue following this pattern for each letter in the sequence.

Example - 2

Input:
key = 5
Math operation = subtraction
word = "TOSS"

Output:
BGCC 
Exercise - 1:

Input:
2
addition
DTTDCK

Output:
YIIYZR 
