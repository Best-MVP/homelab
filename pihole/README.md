Test dnscrypt resolving

```shell
docker run --rm -it --network homelab --link dnscrypt uzyexe/drill -p 5053 dnscrypt.info @dnscrypt
```

Test pihole resolving. Replace 192.168.1.114 with your lab server IP.

```shell
dig @192.168.1.114 google.com
```
