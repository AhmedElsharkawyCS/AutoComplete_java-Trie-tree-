# AutoComplete_java-Trie-tree-

about::Trie (Keyword Tree)

Strings can essentially be viewed as the most important and common topics for a variety of programming problems. String processing has a variety of real world applications too, such as:

Search Engines
Genome Analysis
Data Analytics
All the content presented to us in textual form can be visualized as nothing but just strings.

Tries:

Tries are an extremely special and useful data-structure that are based on the prefix of a string. They are used to represent the “Retrieval” of data and thus the name Trie.

Prefix : What is prefix:

The prefix of a string is nothing but any n letters n≤|S| that can be considered beginning strictly from the starting of a string. For example , the word “abacaba” has the following prefixes:

a
ab
aba
abac
abaca
abacab

A Trie is a special data structure used to store strings that can be visualized like a graph. It consists of nodes and edges. Each node consists of at max 26 children and edges connect each parent node to its children. These 26 pointers are nothing but pointers for each of the 26 letters of the English alphabet A separate edge is maintained for every edge.

Strings are stored in a top to bottom manner on the basis of their prefix in a trie. All prefixes of length 1 are stored at until level 1, all prefixes of length 2 are sorted at until level 2 and so on.
