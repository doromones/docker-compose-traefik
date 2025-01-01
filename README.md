```
cd traefik/certs
CAROOT=$(pwd) mkcert -install
CAROOT=$(pwd) mkcert traefik.local
CAROOT=$(pwd) mkcert whoami.local
CAROOT=$(pwd) mkcert my-development-domain.local
```