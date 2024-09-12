<!-- As you can see, each character of the reassigned string gets printed inside the loop.

Go back to the original string by deleting the text reassignment. -->

text = 'Hello World'
shift = 3
alphabet = 'abcdefghijklmnopqrstuvwxyz'

for char in text.lower():
    index = alphabet.find(char)
    print(char, index)
    new_index = index + shift
