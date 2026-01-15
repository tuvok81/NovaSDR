Add https Function
-------------------------------------
TESTED on Ubuntu 24.04.3 LTS


please create on the NovaSDR Dir your Certificate

```sh
openssl req -x509 -newkey rsa:2048 -nodes -keyout certs/privkey.pem -out certs/fullchain.pem   -days 365 -subj "/CN=YOUR.SDR-DOMAIN.COM"
```
The names of the certificates are based on letsencrypt if you want to use that.
