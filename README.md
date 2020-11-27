## NGINX

#### Nginx can act as a:

    1. Proxy (Layer 7, Layer 4)
    2. Reverse Proxy
    3. Load Balancer
    4. Web Server
    and many more.

#### Default configuration file path: /usr/local/etc/nginx/nginx.conf

1. Spin 4 Docker node application at ports 2222, 3333, 4444, 5555 respectively
2. Start running them.

- NginX by default, uses round-robin algorithm to balance load between servers.
