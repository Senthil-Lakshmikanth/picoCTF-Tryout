# Forensics
## information
exiftool <file_name> command is used to extract information of the image. Two base64 numbers is obtained, Giving it into base64 decoder, Flag is obtained in the second one.
## Matryoshka doll
binwalk -e <file_name> command is used to look over the embedded file. Using the command 4 times in a sequential order, we get flag.txt at last and opening it in terminal we get the flag.
## tunn3l v1s10n
A BMP image is downloaded, opening it in hex editor, and googling for BMP file format. Enter the hexa decimal number in correct row and column as mentioned in the wikipedia.
## Glory of the Garden
Opening the image in hex editior and searching for the word "pico", we get the flag.
