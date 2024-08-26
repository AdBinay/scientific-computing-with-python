<!-- .find() returns the index of the matching character inside the string. If the character is not found, it returns -1. As you can see, the first character in text, uppercase 'H', is not found, since alphabet contains only lowercase letters.

You can transform a string into its lowercase equivalent with the .lower() method. Add another print() call to print text.lower() and see the output. -->

text = 'Hello World'
shift = 3
alphabet = 'abcdefghijklmnopqrstuvwxyz'
index = alphabet.find(text[0])
print(index)
print(text.lower())