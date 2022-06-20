# H-SSL-UTILS

SSL issuing and configuration scripts.

## Prerequisites

- POSIX Shell.
- certbot for Letsencrypt.
- OpenSSL binaries.
- OpenSSH utilities.

## Help

hdkim

    Usage: hdkim ...
    
    This script helps configuring DKIM.
    - https://prefetch.eu/blog/2020/email-server/
    - https://www.mail-tester.com/
    
    show                   : Show configuration.
    
    create [SELECTOR]      : Create public and private keys for DKIM.
    list                   : List DKIM keys.
    
    assign     DOMAIN SELECTOR : Assign a selector to a domain.
    selector   DOMAIN          : Print the selector for the domain.
    dns-record DOMAIN          : Print the DKIM DNS record for DOMAIN.

hgencrt

    Usage: hgencrt ...
    
    This script helps issuing certificates using `letsencrypt` in remote
    hosts using ssh tunneling.
    
    ... show         : Show configuration.
    
    ... issue DOMAIN...    : Issue certificate for the DOMAIN.
    ... ssh-redirect   SSL : Open redirection in remote machine, shutdown http.
    ... ssh-unredirect SSL : Close redirection, restart http.
    ... del DOMAIN...      : Delete certificates.
    
    ... ls-bare            : List domains.
    ... ls                 : List domains with expiration dates.
    
    ... install SSL|- DOMAIN... : Install certificates.
    ... allow   SSL|- USER...   : Allow users to read SSL certificates.

## HDKIM

    Usage: hdkim ...
    
    This script helps configuring DKIM.
    - https://prefetch.eu/blog/2020/email-server/
    - https://www.mail-tester.com/
    
    show                   : Show configuration.
    
    create [SELECTOR]      : Create public and private keys for DKIM.
    list                   : List DKIM keys.
    
    assign     DOMAIN SELECTOR : Assign a selector to a domain.
    selector   DOMAIN          : Print the selector for the domain.
    dns-record DOMAIN          : Print the DKIM DNS record for DOMAIN.


hgencrt

## HGENCRT

    Usage: hgencrt ...
    
    This script helps issuing certificates using `letsencrypt` in remote
    hosts using ssh tunneling.
    
    ... show         : Show configuration.
    
    ... issue DOMAIN...    : Issue certificate for the DOMAIN.
    ... ssh-redirect   SSL : Open redirection in remote machine, shutdown http.
    ... ssh-unredirect SSL : Close redirection, restart http.
    ... del DOMAIN...      : Delete certificates.
    
    ... ls-bare            : List domains.
    ... ls                 : List domains with expiration dates.
    
    ... install SSL|- DOMAIN... : Install certificates.
    ... allow   SSL|- USER...   : Allow users to read SSL certificates.


## Collaborating

For making bug reports, feature requests and donations visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)

