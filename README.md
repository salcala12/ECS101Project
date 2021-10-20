# ECS101Project
# Shaw 3344
# Text to Binary


S_lower_bit = ["e", "t", "a", "o", "i", "n", "s", "r", "E", "T", "A", "O", "I", "N", "S", "R"]
L_lower_bit = ["h", "l", "d", "c", "u", "m", "f", "p", "g", "w", "y", "b", "v", "k", "x", "j", "q", "z", "H", "L", "D", "C", "U", "M", "F", "P", "G", "W", "Y", "B", "V", "K", "X", "J", "Q", "Z"]
Special_bit = [".", ",", "-", "!", "'", '"', " ", "\n"]
def text_to_binary(paper: str)-> str:
   binary = ""
   for item in paper:
       if item in S_lower_bit:
           binary += "1"
       if item in L_lower_bit:
           binary += "0"
       if item in Special_bit:
           binary += "0"
       if item == "e":
           binary += "0000"
       if item == "t":
           binary += "0001"
       if item == "a":
           binary += "0010"
       if item == "o":
           binary += "0011"
       if item == "i":
           binary += "0100"
       if item == "n":
           binary += "0101"
       if item == "s":
           binary += "0110"
       if item == "r":
           binary += "0111"
       if item == "E":
           binary += "1000"
       if item == "T":
           binary += "1001"
       if item == "A":
           binary += "1010"
       if item == "O":
           binary += "1011"
       if item == "I":
           binary += "1100"
       if item == "N":
           binary += "1101"
       if item == "S":
           binary += "1110"
       if item == "R":
           binary += "1111"
       if item == "h":
           binary += "000000"
       if item == "l":
           binary += "000001"
       if item == "d":
           binary += "000010"
       if item == "c":
           binary += "000011"
       if item == "u":
           binary += "000100"
       if item == "m":
           binary += "000101"
       if item == "f":
           binary += "000110"
       if item == "p":
           binary += "000111"
       if item == "g":
           binary += "001000"
       if item == "w":
           binary += "001001"
       if item == "y":
           binary += "001010"
       if item == "b":
           binary += "001011"
       if item == "v":
           binary += "001100"
       if item == "k":
           binary += "001101"
       if item == "x":
           binary += "001110"
       if item == "j":
           binary += "001111"
       if item == "q":
           binary += "010000"
       if item == "z":
           binary += "010001"
       if item == "H":
           binary += "010010"
       if item == "L":
           binary += "010011"
       if item == "D":
           binary += "010100"
       if item == "C":
           binary += "010101"
       if item == "U":
           binary += "010110"
       if item == "M":
           binary += "010111"
       if item == "F":
           binary += "011000"
       if item == "P":
           binary += "011001"
       if item == "G":
           binary += "011010"
       if item == "W":
           binary += "011011"
       if item == "Y":
           binary += "011100"
       if item == "B":
           binary += "011101"
       if item == "V":
           binary += "011110"
       if item == "K":
           binary += "011111"
       if item == "X":
           binary += "100000"
       if item == "J":
           binary += "100001"
       if item == "Q":
           binary += "100010"
       if item == "Z":
           binary += "100011"
       if item == ".":
           binary += "100100"
       if item == ",":
           binary += "100101"
       if item == "-":
           binary += "100110"
       if item == "!":
           binary += "100111"
       if item == "'":
           binary += "101000"
       if item == '"':
           binary += "101001"
       if item == " ":
           binary += "101010"
       if item == "\n":
           binary += "101011"
   print(binary)
