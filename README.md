# macro-assembler



#   A macro assembler includes a macroinstruction facility so that (parameterized) assembly language text can be represented by a name, and that name can be used to insert the expanded text into other code
    
   
   
   
 
12/01/20     1.10  Increased buffer size from 128 bytes to 1024 bytes

25/01/20     1.11  General cleanup and more documentation

15/02/20     1.20  Modify ESC handling for full 8087 operation

21/02/20     1.21  Fix date in HEX and PRN files; modify buffer handling

04/03/20     1.22  Fix 1.21 buffer handling

28/03/20     1.23  Re-open source file for listing to allow assembling CON:

21/05/20     1.24  Allow nested IFs

07/06/20     1.25  Add Intel string mnemonics; clean up a little

08/07/20     1.30  Re-write pass 2:
                   Always report errors to console
        	       Exact byte lengths for HEX and PRN files

