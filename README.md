An 8086 Implementation of a 128bit Advanced Encyption Standard (AES)

The Advanced Encryption Standard or AES is a symmetric block cipher used by the U.S. government 
to protect classified information and is implemented in software and hardware throughout the world to
encrypt sensitive data. The AES operates on a 128 bit bursts as well as 128 bits key.

 Requirements
 The implementation of one cycle of AES algorithm as follows:
1) Build two Procedures based on interrupts that reads 128 bits from the user and prints the result on
the screen.
2) Use Macros to implement SubBytes(), ShiftRows(), MixColumns(), AddRoundKey() modules, all
work on 128 bits.
3) For the AddRoundkey module consider the used key of FF FF FF FF FF FF FF FF FF FF
4) MixColumns is a bit tough, and needs extra work its clear description is available in this 
document. Try to start with others first to get better feeling:
http://www.angelfire.com/biz7/atleast/mix_columns.pdf
5) Your main program should use the above Macros and subroutines to read the data from the user
and finalize 10 stages of AES and print the result on the screen.
