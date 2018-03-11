# arpag
Otomatik exploit aracı

"arpağ:Türk mitolojisinde büyülü söz anlamındadır.Exploit etme işlemini otomatik yaptığı için araç adı arpağ seçilmiştir."

Kullanım:
arpag.py [-h] IP_address Exploit_status Port_baslangic Port_bitis

Örnek Kullanım:

python arpag.py 192.168.1.24 False 20 30

192.168.1.24 port taraması yaparak banner bilgisinden muhtemel exploit belirleniyor. Port aralığı 20-30 arasında belirlenmiştir. Exploit_status False olduğu için herhangi bir exploit etme işlemi yapılmayacaktır.

Örnek Çıktı:

python arpag.py 192.168.1.24 False 20 30

[+]Port:  21

[+]Servis: : 220 (vsFTPd 2.3.4)

[+]Port:  22

[+]Servis: : SSH-2.0-OpenSSH_4.7p1 Debian-8ubuntu1

[+]Port:  23

[+]Servis: : ���� ��#��'

[+]Port:  25

[+]Servis: : 220 metasploitable.localdomain ESMTP Postfix (Ubuntu)

[+]Exploit kontrolleri başlıyor...

[+]Serviste exploit kontrolü başlıyor:  220 (vsFTPd 2.3.4)

[+]Metasploit exploit: exploit/unix/ftp/vsftpd_234_backdoor



https://github.com/anilbaranyelken/arpag/blob/master/arpag.JPG
