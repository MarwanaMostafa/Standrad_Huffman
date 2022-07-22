# Standrad_Huffman
compression algorithm implementation using java
Compress:
  1-take an input sentence (one line) to be read from a file and compress it using  Standard Huffman
  2-save the compressed output along with the dictionary to the file(this dictionary will be input for Deompression)
 Decompress file .

## Example :
**input :**

The quick brown fox jumps over the lazy dog
&&
Dictionary is : 000 (space character encoding), w 001000, x 001001, t 001010, v 001011, u 00110, y  001110, z 001111, h 01000, r 01001, e 0101, o 011, l 10000, m 10001, j 10010, k 10011, q 10100, s  10101, n 10110, p 10111, b 11000, c 11001, T 11010, a 11011, g 11100, i 11101, d 11110, f 11111

**Output wil be :** 
1101001000010100010100001101110111001100110001100001001011001000101100001111101100100100010010001101000110111101010000110010110101010010000010100100001010001000011011
0011110011100001111001111100
