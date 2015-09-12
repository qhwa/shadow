This is docker composer config for setting up a high available shadowsocks server.

## usage:

### simple way

~~~sh
docker-compose up
~~~

### more flexiable way

If you need more shadowsocks containers, use `docker-compose scale shadowsocks=N` where `N` is the number you want,
and start a new haproxy container outside of docker-compose.
