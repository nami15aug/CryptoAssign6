# CryptoAssign6
DSA implementation

#Build Setup
1. This implemntation uses openssl/sha and gnu gmp libraries.
2. gmplib is attached in the project
3. 


#Sample Execution Logs

Enter 1 to sign and 0 to verify:1

<=== Signing Operation in progress ===>
Enter a message(in numerals) to sign
1234

sign s1: 18

sign s2: 73

Enter 1 to sign and 0 to verify:0

<=== Verifying in progress ===>

Enter S1,S2,m(in numerals))
18,73,1234

v: 18

 Verification Success!

Enter 1 to sign and 0 to verify:0

<=== Verifying in progress ===>

Enter S1,S2,m(in numerals))
1,5,1234

v: 35

 Verification Failed!

Enter 1 to sign and 0 to verify:
