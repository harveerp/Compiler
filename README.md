Compiler
========
Created a compiler, which takes in a variation of C language. The compiler consisted of four phases. First, the scanner acted as a lexical analyzer that read characters from a file and transformed the stream of characters into tokens. Second, the parser read in the tokens to make them grammatically correct. The parser mainly focused on recognition of syntactic structure of a correct program. The third stage was the semantic analyzer that took the input of the parser and created a symbol table. Finally, a code generator generated the code for compiler for the virtual machine so it could be executed.
