Arpag - Automatic Exploit Tool

arpağ: In Turkish mythology magical word means. The tool name arpag has been selected because it has made the exploit process automatic.

Installation:

git clone https://github.com/anilbaranyelken/arpag.git

cd tulpar

pip install -r requests

Usage:

arpag.py [-h] IP_address Exploit_status Port_baslangic Port_bitis

Example Usage 1:

python arpag.py 192.168.1.24 False 20 30

192.168.1.24 , The IP address is scanned for the port and banner information is received. The port range is 20-30. Exploit_status is False, no exploit will be done.

Output:

python arpag.py 192.168.1.24 False 20 30

[+]Port: 21

[+]Servis: : 220 (vsFTPd 2.3.4)

[+]Port: 22

[+]Servis: : SSH-2.0-OpenSSH_4.7p1 Debian-8ubuntu1

[+]Port: 23

[+]Servis: : ����� ��#��'

[+]Port: 25

[+]Servis: : 220 metasploitable.localdomain ESMTP Postfix (Ubuntu)

[+]Exploit kontrolleri başlıyor...

[+]Serviste exploit kontrolü başlıyor: 220 (vsFTPd 2.3.4)

[+]Metasploit exploit: exploit/unix/ftp/vsftpd_234_backdoor

<img src="https://github.com/anilbaranyelken/arpag/blob/master/arpagExploitFalse.JPG">
 
Example Usage 2:

python arpag.py 192.168.1.24 True 1 80

[+]Port: 21

[+]Servis: : 220 (vsFTPd 2.3.4)

[+]Port: 22

[+]Servis: : SSH-2.0-OpenSSH_4.7p1 Debian-8ubuntu1

[+]Port: 23

[+]Servis: : ����� ��#��'

[+]Port: 25

[+]Servis: : 220 metasploitable.localdomain ESMTP Postfix (Ubuntu)

[+]Exploit kontrolleri başlıyor...

[+]Serviste exploit kontrolü başlıyor: 220 (vsFTPd 2.3.4)

[+]Metasploit exploit: exploit/unix/ftp/vsftpd_234_backdoor

<img src="https://github.com/anilbaranyelken/arpag/blob/master/arpag.JPG">

