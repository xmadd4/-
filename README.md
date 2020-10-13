Ketik command dibawah ini:
<br>
$apt update
<br>
$apt upgrade
<br>
$pkg install tor
<br>
$pkg install nano
<br>
$pkg install php
<br>
<br>
Tunggu hingga proses selesai
<br>
<br>
Jika sudah 
<br>
$cd ..
<br>
$cd usr/etc/tor
<br>
$nano torrc
<br>
<br>
Samakan dengan dibawah ini:
<br>
<br>
## Once you have configured a hidden service, you can look at the
## contents of the file ".../hidden_service/hostname" for the address
## to tell people.
##
## HiddenServicePort x y:z says to redirect requests on port x to the
## address y:z.

HiddenServiceDir /data/data/com.termux/files/home
HiddenServicePort 80 127.0.0.1:8080

#HiddenServiceDir /data/data/com.termux/files/usr/var/lib/tor/other_hidden_service/
#HiddenServicePort 80 127.0.0.1:80
#HiddenServicePort 22 127.0.0.1:22

################ This section is just for relays #####################
<br>
Lalu ctrl+x 
<br>
Y
<br>
Lalu cd
<br>
Nano index.php
<br>
<center><h1><font color="red">Website Darknet</font></h1></center>
<br>
<br>
Ini cuma sebagai contoh
<br>
Ctrl + x Y
<br>
Lalu buka terminal baru
<br>
$tor
<br>
Lalu buka terminal baru lagi
<br>
$cd
<br>
$cat hostname
<br>

Thanks .. by 4.D
