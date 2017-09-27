# Useful articles to make a good server hardening
## Public Key Pinning
- https://developer.mozilla.org/en-US/docs/Web/HTTP/Public_Key_Pinning
- https://raymii.org/s/articles/HTTP_Public_Key_Pinning_Extension_HPKP.html

## HTTP Strict Transport Security
- https://raymii.org/s/tutorials/HTTP_Strict_Transport_Security_for_Apache_NGINX_and_Lighttpd.html

## SSH Server CBC Mode Ciphers to be disabled
- http://linux.uits.uconn.edu/2014/06/25/ssh-weak-ciphers-and-mac-algorithms/

## SSH Weak MAC Algorithms to be disabled
- https://developer.ibm.com/answers/questions/187318/faq-how-do-i-disable-cipher-block-chaining-cbc-mod.html

## Disabling ICMP Timestamp
```/etc/ufw/before.rules``` - ICMP rules (change ACCEPT to DROP) or totally remove them

## How to get A+ grade on SSL Labs tool
- https://community.letsencrypt.org/t/howto-a-with-all-100-s-on-ssl-labs-test-using-apache2-4-read-warnings/2436

## Tools
- https://www.ssllabs.com/ssltest/analyze.html
- https://www.htbridge.com/websec/

## Other notes
1. Disable (the best all) 3rd party scripts on pages with sensitive param in the URL to prevent Cross-domain Referer Leakage.
2. Cookies always with HttpOnly and Secure flags.
3. Always change cookie session name per project.
