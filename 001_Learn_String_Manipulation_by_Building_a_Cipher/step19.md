<!-- Declare a new variable named shifted. Use the bracket notation to access the value of alphabet at index index and assign it to your new variable. -->

text = 'Hello World'
shift = 3
alphabet = 'abcdefghijklmnopqrstuvwxyz'
index = alphabet.find(text[0].lower())
print(index)
shifted = alphabet[index]