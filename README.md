# File-Compression-Using-Huffman-Coding-Algorithm-
Approach: 
Huffman coding is a lossless data compression algorithm. The idea is to assign variable-length codes to input characters, lengths of the assigned codes are based on the frequencies of corresponding characters. The most frequent character gets the smallest code and the least frequent character gets the largest code.
Huffman Algorithm is an efficient way for file
Compression and Decompression. This program exactly
follows Huffman algorithm. It reads frequent characters from
input file and replace it with shorter binary codeword. The
original file can be produced again without losing any bit.
Huffman encoding is widely used in compression formats like
GZIP, PKZIP (winzip) and BZIP2 . Huffman encoding still
dominates the compression industry since newer arithmetic
and range coding schemes are avoided due to their patent
issues.

Algorithm:

1.Start
2.Create a sample file containing data in string format.
3. Read each and every character from file and store it in a
string.
4.Calculate frequency of each character and display it.
5.Implement Huffman logic to build a tree of elements in
priority queue.
6.Return root.
7.Encode or encrypt a character as a leaf node in tree and
assign 0 to left node and 1 to right node while traversing.
8.return codes of each character in string.
9.decode the codes of each character in string and return it.
10.Store the contents of string into file(.dat).
11.Display or open file.
12.Stop.

Complexity Analysis: The time complexity of the Huffman
algorithm is O(nlogn). Using a heap to store the weight of
each tree, each iteration requires O(logn) time to determine
the cheapest weight and insert the new weight. There are O(n)
iterations, one for each item.
