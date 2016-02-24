Reference
-----

smtpcode is used to explain the meaning of an HTTP status code on the command line
Inspired by httpcode: https://github.com/rspivak/httpcode

SMTP from IANA: http://www.iana.org/assignments/smtp-enhanced-status-codes/smtp-enhanced-status-codes.xhtml#smtp-enhanced-status-codes-3
SMTP reply codes: http://kb.kerio.com/assets/smtp_reply_codes.pdf
SMTP status codes: http://kb.kerio.com/assets/smtp_status_codes.pdf
curl and SMTP: http://www.slashroot.in/curl-command-tutorial-linux-example-usage

Usage
-----

Explain 250 status code

::
    $ smtpcode 250
    250 Requested mail action okay, completed

List all codes

::
    $ smtpcode
    200 (nonstandard success response, see rfc876)
    211 System status, or system help reply
    214 Help message
    220 <domain> Service ready

    ...

Show help

::
    $ smtpcode -h
    Without parameters lists all available
    smtp reply codes and their description
    
    Options:
    -h, --help            show this help message and exit
