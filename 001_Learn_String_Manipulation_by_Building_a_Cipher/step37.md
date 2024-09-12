<!-- Now, replace new_char with encrypted_text. Also, modify the print() call into print('char:', char, 'encrypted text:', encrypted_text) to reflect this change. -->

text = 'Hello World'
shift = 3
alphabet = 'abcdefghijklmnopqrstuvwxyz'
encrypted_text = ''

for char in text.lower():
    index = alphabet.find(char)    
    new_index = index + shift
    encrypted_text = alphabet[new_index]
    print('char:', char, 'encrypted text:', encrypted_text)