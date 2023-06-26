### rainloop-webmail
-------------------------------------------------------------------------------------------------------------------------------
This is a simple tutorial helping your to implement your own mail server on an ubuntu machine.

### main part: necessary elements for our mail server we need to install
-------------------------------------------------------------------------------------------------------------------------------
- SMTP Server = Postfix
- IMAP Server = Dovecot
- WEB SERVER = Nginx
- WEB MAIL = rainloop

### Security layers
-------------------------------------------------------------------------------------------------------------------------------
- Setup SPF & DKIM with POSTFIX
- Enable https on nginx
- Redirect-http-to-https for Nginx
- INSTALL WAF for NGINX = NGINX ModeSecurity
