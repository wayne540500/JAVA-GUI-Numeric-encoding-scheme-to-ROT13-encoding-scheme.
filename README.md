# JAVA-GUI-Numeric-encoding-scheme-to-ROT13-encoding-scheme.

This is an application where you type a word and encode the word with different schemes. We have two schemes, the Numeric encoding scheme and the ROT13 encoding scheme. “Numeric” converts a string of letters to a string of numbers. Thus, “abcdef” will be encoded to “1.2.3.4.5.6.” Node that we have a “.” Separating each number.

![image](https://github.com/wayne540500/JAVA-GUI-Numeric-encoding-scheme-to-ROT13-encoding-scheme./assets/69573286/bdd15ead-e96e-47da-bc78-6b51c4a47417)


“ROT13” encoding is short for “rotate 13”. This rotates the letter by 13 places. Since there are 26 letters in the alphabet, ROT13 encoding a string twice will give the original result. Thus, “abcdef” will be encoded to “nopqrs”, and the string “nopqrs” will be ROT13 encoded to “abcdef”.

![image](https://github.com/wayne540500/JAVA-GUI-Numeric-encoding-scheme-to-ROT13-encoding-scheme./assets/69573286/d9c972d0-19bc-471a-9017-652cd0e96cd0)

This should also support the use of the JFileChooser. Under the File menu there should be an “Open” menu item which when you select it will open the JFileChooser. You should be able to select the file sample.txt and have the contents read into the input area and output the encoded form.

![image](https://github.com/wayne540500/JAVA-GUI-Numeric-encoding-scheme-to-ROT13-encoding-scheme./assets/69573286/a2125b1d-5a7b-4bec-b1fb-9fe8cfbcb7d7)

![image](https://github.com/wayne540500/JAVA-GUI-Numeric-encoding-scheme-to-ROT13-encoding-scheme./assets/69573286/2c8c3bf8-0ec1-4abe-bf5b-7ae67cf84043)

remember that characters have a “numerical” value. The value of (‘c’ – ‘a’ + 1) = 3
3 + ‘a’ – 1 = ‘c’
text fields can take a “CaretListener” which will run every time the cursor is moved.
