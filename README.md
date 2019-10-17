# String-Operations
## Aim
To learn about Strings and various String Operations in C
## Theory
String is an array of characters. String.h header file supports all the string functions in C language. All the string functions are given below.
String functions and Description:
strcat ( )     -Concatenates str2 at the end of str1
strncat ( )    -Appends a portion of string to another
strcpy ( )     -Copies str2 into str1
strncpy ( ) 	 -Copies given number of characters of one string to another
strlen ( ) 	   -Gives the length of str1
strcmp ( ) 	   -Returns 0 if str1 is same as str2. Returns <0 if strl < str2. Returns >0 if str1 > str2
strcmpi ( ) 	 -Same as strcmp() function. But, this function negotiates case.  “A” and “a” are treated as same.
strchr ( ) 	   -Returns pointer to first occurrence of char in str1
strrchr ( ) 	 -last occurrence of given character in a string is found
strstr ( ) 	   -Returns pointer to first occurrence of str2 in str1
strrstr ( ) 	 -Returns pointer to last occurrence of str2 in str1
strdup ( ) 	   -Duplicates the string
strlwr ( ) 	   -Converts string to lowercase
strupr ( ) 	   -Converts string to uppercase
strrev ( ) 	   -Reverses the given string
strset ( ) 	   -Sets all character in a string to given character
strnset ( ) 	 -It sets the portion of characters in a string to given character
strtok ( ) 	   -Tokenizing given string using delimiter
