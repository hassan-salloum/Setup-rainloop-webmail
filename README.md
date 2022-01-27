# rainloop-webmail
HOW TO BUILD YOUR OWN MAIL SERVER ON UBUNTU

This is a simple tutorial helping your to implement your own mail server on an ubuntu machine:

### main part: necessary elements for our mail server we need to install
- SMTP Server = Postfix
- IMAP Server = Dovecot
- WEB SERVER = Nginx
- WEB MAIL = rainloop

### Security layers
- SPF & DKIM with Postfix on Debian Server
- enable-https-nginx
- nginx-redirect-http-to-https
- INSTALL WAF (NGINX ModeSecurity)
