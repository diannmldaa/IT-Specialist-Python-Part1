# IT-Specialist-Python-Part1

There are 7 data types that are often used by programmers in Python i.e number such as integer and float, boolean, string, list, tuple, set, and dictionary.
all with different usage and built-in that comes with it.

### Number ###
* Integer or int is a whole number, positive or negative, without decimals, of unlimited length
* Float or "floating point number" is a number, positive or negative, containing one or more decimals.
* Complex numbers are represented as A+Bi or A+Bj, where A is real part and B is imaginary part.

### Boolean ###
* It's often used for returned value on comparison an expression
* Has a `True` or a `False` value

### String ###
* String is collection of alphabets, words and characters
* Python has a built-in string class named `str`
* String are "immutable" which means they cannot be changed after they are created

__1. Modify String__
* The `upper()` method returns a string where all characters are in upper case
* The `lower()` method returns a string where all characters are in lower case
* Remove Whitespace
    * The `rstrip()` method removes any trailing characters (characters at the end a string), space is the default trailing character to remove.
    * The `lstrip()` method removes any leading characters (space is the default leading character to remove)
    * The `strip()` method removes any leading (spaces at the beginning) and trailing (spaces at the end) characters (space is the default leading character to remove)
* The `replace()` method replaces a specified phrase with another specified phrase.

__2. Formatting String__  
* The `zfill()` method will fill the string with a specified number of 0 values at the beginning. The type data must be string, whether not string, must be converted first
* `rjust()`
    * The `rjust()` method used to make text right-aligned.
    * This method will add a space to the string to make it match.
    * The parameter is an integer which is the overall length of the text (not the number of spaces added).
    * We can replace the whitespace with another symbol by entering the second paramete
* `ljust()`
    * The rjust() method used to make text left-aligned.
    * This method will add a space to the string to make it match.
    * The parameter is an integer which is the overall length of the text (not the number of spaces added).
    * We can replace the whitespace with another symbol by entering the second parameter.
* `center()`
    * The rjust() method used to make text centered.
    * This method will add a space to the string to make it match.
    * The parameter is an integer which is the overall length of the text (not the number of spaces added).
    * We can replace the whitespace with another symbol by entering the second parameter.

__3. Escape characters__
* To insert characters that are illegal in a string, use an escape character.
* An escape character is a backslash `\` followed by the character you want to insert.
* An example of an illegal character is a double quote inside a string that is surrounded by double quotes

__4. String Checking__
* The `startswith()` method returns True if the string starts with the specified value, otherwise False
* The `endswith()` method returns True if the string end with the specified value, otherwise False
* The `isupper()` method is checks whether all the case-based characters (letters) of the string are uppercase and it will be returned `True` if all characters on  a string are in uppercase and `False` if otherwise
* The `islower()` method is checks whether all the case-based characters (letters) of the string are lowercase and it will be returned `True` if all characters on  a string are in lowercase and `False` if otherwise
* The `isalpha()` method checks whether all characters of the string are alphabet and it will be returned `True` if all character on a string are alphabetic and `False` if otherwise
* The `isalnum()` method checks whether all characters of the string are alphanumeric and it will be returned `True` if all character on a string are alphanumeric and `False` if otherwise
* The `isdecimal()` method returns `True` if all the characters are decimals (0-9)
* The `istitle()` method returns `True` if all words in a text start with a upper case letter, AND the rest of the word are lower case letters, otherwise `False`
* The`isspace()`  method returns `True` if all the characters in a string are whitespaces, otherwise `False`

__5. Slicing String__  

### List ###
* Lists are used to store multiple items in a single variable.
* To declare a list, brackets `[]` are used and each member is separated by a comma.
* List items are indexed, the index start form 0
* List items are ordered, changeable, and allow duplicate values
* Lists can contain members of the same or different types

__1. Python List Method__
* The `del` keyword is used to delete an object or an element in an object
* The `len()` method will return the sum of the total items in an object. on a string, this function will return the number of characters
* The `append()` method is used to add an item at the end of an object
* The `extend()` method adds all elements of the iterable to the end of the list.
* The `insert()` method inserts an element into the object according to the index specified in the parameter
* The `remove()` method removes the first element whose content is equal to the parameter value
* The `pop()` method removes the item according to the index in the parameter and returns the deleted value
* The `index()` method returns the index according to the value written in the parameter
* The `count()` method returns the number of elements in the object that have the same value in the parameter .
* The `sort()` method sorts the list items in ascending order by default
* The `reverse()` method will return list from tail index to head

### Tuple ###
* A tuple is a collection which is ordered, allow duplicate values and unchangeable.
* Tuples are used to store multiple items in a single variable
* Tuples are written with round brackets `()`
* Tuple items can be of any data type

### Set ###
* A set is a collection which is unordered, unchangeable, and unindexed.
* Sets are used to store multiple items in a single variable and must be unique
* Sets are written with curly brackets `{}`
* Set items can be of any data type

__1. Set Method__
* The `union()` method is returned a set that contains all items from the original set, and all items from the specified set(s)

* The `intersection()` method is returned set contains only items that exist in both sets, or in all sets if the comparison is done with more than two sets

### Dictionary ###
* A dictionary is a collection that is unordered, changeable, and do not allow duplicates
* Dictionary items are presented in key:value pairs, and can be referred to by using the key name
* Dictionaries are written with curly brackets `{}`

# I/O Python 
__1. Output__
* Output use `print()` function to output data to standard output device(screen).
* Sometimes use formatting to make `print()` more attractive by using `str.format()` on `print()` parameter or used `%` and print like `sprintf()` on C Language

__2. Input__
* Input use `input()` function to take input from user
* Allow flexibility on programmer with user input
