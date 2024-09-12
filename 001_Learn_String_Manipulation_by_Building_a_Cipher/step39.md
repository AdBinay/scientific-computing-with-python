<!-- You can obtain the same effect of a = a + b by using the addition assignment operator:

Example Code
a += b
The addition assignment operator enables you to add a value to a variable and then assign the result to that variable.

Use the += operator to add a value and assign it at the same time to encrypted_text. -->

text = 'Hello World'
shift = 3
alphabet = 'abcdefghijklmnopqrstuvwxyz'
encrypted_text = ''
for char in text.lower():
    index = alphabet.find(char)
    new_index = index + shift
    encrypted_text += alphabet[new_index]
    print('char:', char, 'encrypted text:', encrypted_text)