# Tcp-proxy
it`s a code for createing TCP proxy`s useing python 


▓█████  ██▀███   ██▀███   ▒█████   ██▀███              █████▒██▓ ▄▄▄     ▄▄▄█████▓
▓█   ▀ ▓██ ▒ ██▒▓██ ▒ ██▒▒██▒  ██▒▓██ ▒ ██▒          ▓██   ▒▓██▒▒████▄   ▓  ██▒ ▓▒
▒███   ▓██ ░▄█ ▒▓██ ░▄█ ▒▒██░  ██▒▓██ ░▄█ ▒          ▒████ ░▒██▒▒██  ▀█▄ ▒ ▓██░ ▒░
▒▓█  ▄ ▒██▀▀█▄  ▒██▀▀█▄  ▒██   ██░▒██▀▀█▄            ░▓█▒  ░░██░░██▄▄▄▄██░ ▓██▓ ░ 
░▒████▒░██▓ ▒██▒░██▓ ▒██▒░ ████▓▒░░██▓ ▒██▒ ██▓  ██▓ ░▒█░   ░██░ ▓█   ▓██▒ ▒██▒ ░ 
░░ ▒░ ░░ ▒▓ ░▒▓░░ ▒▓ ░▒▓░░ ▒░▒░▒░ ░ ▒▓ ░▒▓░ ▒▓▒  ▒▓▒  ▒ ░   ░▓   ▒▒   ▓▒█░ ▒ ░░   
 ░ ░  ░  ░▒ ░ ▒░  ░▒ ░ ▒░  ░ ▒ ▒░   ░▒ ░ ▒░ ░▒   ░▒   ░      ▒ ░  ▒   ▒▒ ░   ░    
   ░     ░░   ░   ░░   ░ ░ ░ ░ ▒    ░░   ░  ░    ░    ░ ░    ▒ ░  ░   ▒    ░      
   ░  ░   ░        ░         ░ ░     ░       ░    ░          ░        ░  ░        
                                             ░    ░                                                    



installing in linux/termux :

git clone <link-project>

cd Tcp-proxy

Useing : ./proxy.py [local_host] [local_port] [remote_host] [remote_port] [receive_first]

Example : ./proxy.py 127.0.0.1 9000 10.12.132.1 9000 True

After running the codes, you should open a socket from the FTP server on your host so :

for Example => ftp 127.0.0.1:9000

Now u should seting up your server setting 

done !!!  
