## 1. postfix (smtp server)
````
postfix/
├── aliases
├── aliases.db
├── body_checks
├── dynamicmaps.cf
├── dynamicmaps.cf.d
├── header_checks
├── ldap_sender_login_maps.cf
├── ldap_virtual_alias_maps.cf
├── ldap_virtual_mailbox_maps.cf
├── main.cf
├── main.cf.proto
├── makedefs.out -> /usr/share/postfix/makedefs.out
├── master.cf
├── master.cf.proto
├── mime_header_checks
├── post-install
├── postfix-files
├── postfix-files.d
│   └── ldap.files
├── postfix-script
├── sasl
│   ├── sasl_passwd
│   └── smtpd.conf
├── virtual_alias_maps
├── virtual_alias_maps.db
└── virtual_domains
````

````
## 2. dovecot (imap server)
dovecot/
├── conf.d
│   ├── 10-auth.conf
│   ├── 10-director.conf
│   ├── 10-logging.conf
│   ├── 10-mail.conf
│   ├── 10-master.conf
│   ├── 10-ssl.conf
│   ├── 10-tcpwrapper.conf
│   ├── 15-lda.conf
│   ├── 15-mailboxes.conf
│   ├── 20-imap.conf
│   ├── 20-lmtp.conf
│   ├── 20-managesieve.conf
│   ├── 20-pop3.conf
│   ├── 90-acl.conf
│   ├── 90-plugin.conf
│   ├── 90-quota.conf
│   ├── 90-sieve-extprograms.conf
│   ├── 90-sieve.conf
│   ├── auth-checkpassword.conf.ext
│   ├── auth-deny.conf.ext
│   ├── auth-dict.conf.ext
│   ├── auth-ldap.conf.ext
│   ├── auth-master.conf.ext
│   ├── auth-oauth2.conf.ext
│   ├── auth-passwdfile.conf.ext
│   ├── auth-sql.conf.ext
│   ├── auth-static.conf.ext
│   └── auth-system.conf.ext
├── dovecot-dict-auth.conf.ext
├── dovecot-dict-sql.conf.ext
├── dovecot-ldap.conf.ext
├── dovecot-oauth2.conf.ext
├── dovecot-sql.conf.ext
├── dovecot.conf
└── private
    ├── dovecot.key -> /etc/ssl/private/ssl-cert-snakeoil.key
    └── dovecot.pem -> /etc/ssl/certs/ssl-cert-snakeoil.pem
````
