Ketik command dibawah ini

$apt update 
$apt upgrade
$pkg install tor
$pkg install nano
$pkg install php

Tunggu hingga proses selesai

Jika sudah 
$cd ..
$cd usr/etc/tor
$nano torrc

Samakan dengan dibawah ini:

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

Lalu ctrl+x 
Y

Lalu cd
Nano index.php
<center><h1><font color="red">Website Darknet ku</font></h1></center>


Ini cuma sebagai contoh
Ctrl + x Y

Lalu buka terminal baru
$tor

Lalu buka terminal baru lagi

$cd
$cat hostname


Thanks .. by 4.D
