Posty Ansible script
=============

Ansible script allowing to install a fully functional postfix server with IMAP & SMTP.
List of installed packages :
- [postfix](http://www.postfix.org/) : mail server SMTP
- [dovecot](http://www.dovecot.org/) : IMAP & POP3 service
- [spamassasin](http://spamassassin.apache.org/) : to protect from spam
- [munin](http://munin-monitoring.org/) : for server monitoring (optional)
- [postyAPI](http://posty-soft.org/) : for postfix administration
- [roundcube](http://roundcube.net/) : webmail client (optional)

We are currently finishing this script : it will be released soon enough...
As our configuration can be a bit specific the purpose of this open source project is to make sure that we build together a script easy to parameter for any usage.
