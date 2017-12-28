# nginx-service-for-systemd-with-naxsi
nginx service file for systemd when compiling following naxsi documentation

OS : Debian stretch

Location : /lib/systemd/system/nginx.service

to do :

#Enable at boot
systemctl enable nginx.service
#Check
systemctl list-units

FYI -> nginx compilation

./configure --add-module=../naxsi-master/naxsi_src/
make
make install
