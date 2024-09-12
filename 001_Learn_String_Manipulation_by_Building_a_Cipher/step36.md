<!-- At the moment, the encrypted character is updated in every iteration. It would be better to store the encrypted string in a new variable. Before your for loop, declare a variable called encrypted_text and assign an empty string ('') to this variable. -->

text = 'Hello World'
shift = 3
alphabet = 'abcdefghijklmnopqrstuvwxyz'
encrypted_text=''

for char in text.lower():
    index = alphabet.find(char)
    new_index = index + shift
    new_char = alphabet[new_index]
    print('char:', char, 'new char:', new_char)