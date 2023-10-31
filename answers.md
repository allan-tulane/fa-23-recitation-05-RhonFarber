# CMPS 2200 Recitation 6
## Answers

**Name:** Rhon Farber


Place all written answers from `recitation-06.md` here for easier grading.



- **d.**

|        File | Fixed-Length Coding |       Huffman Coding |  Huffman vs. Fixed-Length |
|-------------|---------------------|----------------------|---------------------------|
|       f1.txt|                1340 |                  826 |                  0.616418 |
|  alice29.txt|             1039367 |               676374 |                  0.650756 |
| asyoulik.txt|              876253 |               606448 |                  0.692092 |
| grammar.lsp |               26047 |                17356 |                  0.666334 |
|    fields.c |               78050 |                56206 |                  0.720128 |

The consistent trend is that fixed-length coding is always greater than the Huffman cost. Also, the ratio of huffman vs. fixed-length are fairly similar despite the ranging lengths of the documents.

- **e.**
On a document in which every character had the same frequency with alphabet Sigma all of the frequencies would equal each other so the expected cost would be the frequency times the encodings’ lengths, i.e., a balanced tree of n leaves * log n = total cost of nlogn for all the documents.  

