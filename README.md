# docker-mail-server
mailserver with docker and web mail client by docker-composer

## Edit Caddyfile to make webmail client rainloop work


http://<  URL  > {
  proxy / rainloop:8888 {
    transparent
  }
}
