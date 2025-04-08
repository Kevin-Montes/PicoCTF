# PicoCTF

hashcrack
You wouldacess the server using nc verbal-sleep.picoctf.net 57819 and it would spit out a bunvh a text and give you a has to crack i just guessed which hash type it would be until it worked. I used hashcat and rockyou wordlist to crack each of the hashes which in order from firast to last went md5, and was password123, second was SHA-1 and was letmein. third was SHA-256 and was qwert098u and gave me the flag 
picoCTF{UseStr0nG_h@shEs_&PaSswDs!_869e658e}


EVEN RSA CAN BE BROKEN
I connected the program with the netcat comand they gave me nc verbal-sleep.picoctf.net 50510
once i connected it spat out an N and an e and i ran it into a decoder online and it spat out the flag.
picoCTF{tw0_1$_pr!m3f995d086}
