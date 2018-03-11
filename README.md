# nginx-echo
   $ wget 'http://nginx.org/download/nginx-1.11.2.tar.gz'
   $ tar -xzvf nginx-1.11.2.tar.gz
   $ cd nginx-1.11.2/

   # Here we assume you would install you nginx under /opt/nginx/.
   $ ./configure --prefix=/opt/nginx \
     --add-module=/path/to/echo-nginx-module

   $ make -j2
   $ make install
 https://github.com/openresty/echo-nginx-module#installation
