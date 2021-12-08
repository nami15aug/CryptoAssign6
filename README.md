# CryptoAssign6
DSA implementation

#Build Setup
1. This implemntation uses openssl/sha and gnu gmp libraries.
2. gmplib is attached in the project
3. OpenSSL libraries must be installed in the system - https://drive.google.com/file/d/1PrE7rD1c9utdYSWAZLXiT-VlLMKTP_tB/view?usp=sharing
4. Add the following Linker libraries in codeblocks project . Project -> Build Options -> Debug -> Linker Settings. Note - Update the paths as per the installed directories in your system. 
..\Program Files\OpenSSL-Win64\lib\libcrypto.lib ......\Program Files\OpenSSL-Win64\lib\libssl.lib
..\gmp-6.2.1-mingw-msvc-main\mingw64\lib\gmp.lib
5. Add the include file path in codeblocks project. Project -> Build Options -> Debug -> Search Directories Note - Update the paths as per the installed directories in your system. 
..\Program Files\OpenSSL-Win64\include\
..\gmp-6.2.1-mingw-msvc-main\mingw64\include


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
