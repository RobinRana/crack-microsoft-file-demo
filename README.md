# targets
Target files to hack

Here, you will find: 
A microsoft office doc with a password on it


1)cd crack-microsoft-file-demo
______________________________________________________________________
note:--> python johnHash.py (your target file name) > hash.txt
my target is passwordprotected.docx
_________________________________________________________________________

2)python johnHash.py passwordprotect.docx > hash.txt
3)cat hash.txt

and you see 

passwordprotect.docx:$office$*2010*100000*128*16*ff5c49194a94e82aec585562291f8e23*8b26503872d9a101a08375c912a2895e*005cdb26acb533a2717034666c70828c4dc9675b239364f94bc1c24465eed22a


then you write this command 

4)john --wordlist=/usr/share/wordlists/nmap.lst hash.txt


and you see password is crack

