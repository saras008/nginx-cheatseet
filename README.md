# nginx-cheatseet
#### Install nginx from source
```
root@linux:~# wget https://www.openssl.org/source/openssl-1.1.0i.tar.gz

root@linux:~# tar zxfz https://www.openssl.org/source/openssl-1.1.0i.tar.gz

root@linux:~# ./configure --prefix=/opt/nginx --with-openssl=/home/$user/source/openssl-1.1.0i --with-http_v2_module --with-http_ssl_module --with-http_stub_status_module \
	--with-http_dav_module --with-file-aio --with-threads --with-http_geoip_module --with-stream

root@linux:~# make  && make install

```