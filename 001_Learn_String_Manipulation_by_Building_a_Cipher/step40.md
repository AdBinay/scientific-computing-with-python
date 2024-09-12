<!-- Comparison operators allow you to compare two objects based on their values. You can use a comparison operator by placing it between the objects you want to compare. They return a Boolean value — namely True or False — depending on the truthfulness of the expression.

Python has the following comparison operators:

Operator	Meaning
==	Equal
!=	Not equal
>	Greater than
<	Less than
>=	Greater than or equal to
<=	Less than or equal to

At the beginning of your loop body, print the result of comparing char with a space (' '). Use the equality operator == for that. -->


text = 'Hello World'
shift = 3
alphabet = 'abcdefghijklmnopqrstuvwxyz'
encrypted_text = ''

for char in text.lower():
    print(char == ' ')
    index = alphabet.find(char)
    new_index = index + shift
    encrypted_text += alphabet[new_index]
    print('char:', char, 'encrypted text:', encrypted_text)