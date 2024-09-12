<!-- Clean the output a bit. Delete print(char, index), and turn the last print() call into print('char:', char, 'new char:', new_char). -->

text = 'Hello World'
shift = 3
alphabet = 'abcdefghijklmnopqrstuvwxyz'

for char in text.lower():
    index = alphabet.find(char)
    new_index = index + shift
    new_char = alphabet[new_index]
    print('char:', char, 'new char:', new_char)