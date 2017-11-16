# Twofive

Twofive

Description

The secret messages between Santa Claus and his little helpers are usually encoded in the 25-language. The 25-alphabet is the same as the Latin alphabet with one exception - the letter 'Z' is absent, i.e. the 25-alphabet contains 25 Latin letters from 'A' through 'Y' in the same order as the Latin alphabet. Each word in the 25-language consists of exactly 25 different letters. A word can be written in a 5x5 table filling the rows first; for example, the word ADJPTBEKQUCGLRVFINSWHMOXY will be written as follows:


A	D	J	P	T

B	E	K	Q	U

C	G	L	R	V

F	I	N	S	W

H	M	O	X	Y


A valid word in the 25-language has its letters in each row as well as in each column written in ascending order. Thus, the word ADJPTBEKQUCGLRVFINSWHMOXY is a valid word, in contrast to the word ADJPTBEGQUCKLRVFINSWHMOXY (the ascending order is violated in the second column, and in the third column, too).

Santa Claus has a lexicon. His lexicon is the list of all valid 25-language words in ascending order (lexicographically) along with their ordinal numbers starting from 1. For example, in the lexicon ABCDEFGHIJKLMNOPQRSTUVWXY is the word number 1 and ABCDEFGHIJKLMNOPQRSUTVWXY is the word number 2. In word number 2, U and T are interchanged from their order in word number 1.

Unfortunately, this lexicon is huge. Write a program that determines the ordinal number of an arbitrary given word, and also the word corresponding to a given ordinal number. There are no more than 2^31 words in the lexicon.

Input

Your program is to read from standard input. The first line contains a string with one character: a 'W' or an 'N'. If the first line contains a 'W', then the second line contains a valid 25-language word, that is, a string with 25 characters. If the first line contains an 'N', then the second line contains the ordinal number of an existing 25-language word.

Output

Your program is to write to standard output. If the second line of the input contains a 25-language word, then the line of the output contains the ordinal number of that word. If the second line of the input contains a number, then the line of the output contains the 25-language word with that ordinal number.

Sample Input

W
ABCDEFGHIJKLMNOPQRSUTVWXY

Sample Output

2
