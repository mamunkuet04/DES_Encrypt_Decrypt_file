# DES_Encrypt_Decrypt_file
Encrypt and Decrypt file using DES algorithm using C

/****
*********************** File Encryption and Decryption with DES *********************************/
* version 1.0
*****/

/***
* AUTHOR: ABDHULLAH-AL-MAMUN
* ROLL NO: 1015312001
* EMAIL: mamun_kuet04@yahoo.com, mamun.abdullah@dbbl.com.bd
* PHONE: +88 01779660796
* M.Sc. STUDENT OF IICT, BUET.
* @THIS PROJECT IS DONE AS THE ACHADEMIC PROJECT OF ICT-6541: Applied Cryptography. All right reserved to author.
*
***/

1. PRE-REQUISITE
	A. Put a key file named "key.txt" in the same location of the source code 
	B. Put a input file which you want to encrypt named "input.txt" in the same location of the source code 
	
	
	[The encryptor will generate it's output in the "output.txt" file. And this "output.txt" file will use as input of the decryptor and the decryptor
	will generate its decrypted output in the file "gen_input.txt".]

	
	
2. HOW TO COMPILE AND RUN

## ENCRYPTOR :
  A. FOR COMPILLING ENCRYPTOR PLEASE GIVE THE FOLLOWING COMMAND IN LINUX 
		gcc -o encrypt DES_file_encryptor.c
  
  B. FOR RUNNING ENCRYPTOR PLEASE GIVE THE FOLLOWING COMMAND IN LINUX
	    ./encrypt
		
## DECRYPTOR :
  A. FOR COMPILLING DECRYPTOR PLEASE GIVE THE FOLLOWING COMMAND IN LINUX 
		gcc -o decrypt DES_file_decryptor.c
  
  B. FOR RUNNING CLIENT PLEASE GIVE THE FOLLOWING COMMAND IN LINUX
	    ./decrypt 




/***
* This code has compilled on LINUX. The version is : Red Hat Enterprise Linux Server release 5.5 (Tikanga)
***/




© Abdhullah-Al-Mamun, 1015312001, mamun_kuet04@yahoo.com | mamun.abdullah@dbbl.com.bd , mob:+88 01779660796, IICT, BUET
