# Questions

**Question 1:** How many different variables do you need to control?

Variables to control:
* CMU File Input
* Number of Input files
* Standard Input
* Number of words in file
* Length of word
* Content of each word


**Question 2:** What are the partitions of each variable?
* Number of input files: If the program works for 2 files it should work for N files where N is some integer higher than 2
* Standard input: If the program can handle 2 words in standard input, it should be able to handle N words in standard input where N is some integer higher than 2
* Number of words in a file: If the program works for 1 words in a file it should work for N words in a file where N is some integer higher than 1
* Length of words: If the program works for a word of length 1 it should work for any word with a length between 1 and 129. The program should behave the same for any word with a length greater than 129 and less than 1
* Content of words: Any word that found in the CMU or not should behave the same to any word that is found in the CMU or not found in the CMU. Any word containing illegal characters should behave the same as any word that contains any illegal characters



**Question 3:** What are the normal test values of each variable?

* CMU File Input:
	* CMU file with 1 line
	* CMU file with no comments and less than 150 000 lines
	* CMU file with comments and less than 150 000 lines
	* CMU file with exactly 150 000 lines
	* CMU file with exactly 149 999 lines

* Number of Input Files:
	* One input file
	* Two input files
	* N input files

* Standard input:
	* One standard input word
	* Two standard input words
	* N standard input words

* Number of words in a file:
	* One word
	* Two words
	* N words

* Length of word:
	* One letter
	* Two Letters
	* N letters

* Content of each word
	* Word found in the CMU
	* Word not found in the CMU

**Question 4:** What are the robust test values of each variable?

* CMU File Input:
	* No CMU
	* No permission to open file
	* One single CMU file with 0 lines
	* One single CMU file with exactly 150 001 lines

* Number of Input Files:
	* 0 input files
	* No permission to open file

* Standard input:
	* No input
	* 0 Words

* Number of words in a file:
	* 0 words

* Length of word:
	* 0 length (blank line)
	* 129 characters

* Content of each word
	* Word contains illegal characters
