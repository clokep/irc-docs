A brief history of specifications is given below.  Websites are given where the
official specification lives, but they have all been copied into this directory
for convenience.  Note that some of these links may be broken.

RFCs (http://www.irchelp.org/irchelp/rfc/)
==========================================
* `RFC 1459`_ (original RFC; superseded by `RFC 2810`_ - `RFC 2813`_)
* `RFC 2810`_ (IRC architecture)
* `RFC 2811`_ (IRC channel management)

  * Note: This mostly applies only to servers
* `RFC 2812`_ (IRC client protocol)
* `RFC 2813`_ (IRC server protocol)

  * Note: This applies only to servers
* Summaries of all the numeric codes:

  * http://www.irchelp.org/irchelp/ircd/numerics.html
  * http://www.mirc.net/raws/

.. _RFC 1459: http://tools.ietf.org/html/rfc1459
.. _RFC 2810: http://tools.ietf.org/html/rfc2810
.. _RFC 2811: http://tools.ietf.org/html/rfc2811
.. _RFC 2812: http://tools.ietf.org/html/rfc2812
.. _RFC 2813: http://tools.ietf.org/html/rfc2813

File Transfer / CTCP extensions
===============================
* `CTCP specification`_
* `DCC specification`_ (included fully in the CTCP specification)
* `Updated CTCP specification`_

  * This is not fully supported by clients
* `Turbo DCC`_
* `DCC REVERSE`_
* RDCC
* DCC RSEND
* Reverse/Firewall DCC
* FSERVs
* XDCC_ (eXtended DCC)
* `CTCP/2`_
* SDCC / DCC SCHAT (Secure DCC)
* `DCC Voice`_
* `DCC Resume`_
* `DCC Whiteboard Specification`_
* Overall comparison_ and explanation of the extensions to DCC.

.. _DCC specification: http://www.irchelp.org/irchelp/rfc/dccspec.html
.. _CTCP specification: http://www.alien.net.au/irc/ctcp.txt
.. _Updated CTCP specification: http://www.invlogic.com/irc/ctcp.html
.. _Turbo DCC: http://www.visualirc.net/tech-tdcc.php
.. _DCC REVERSE: http://cvs.epicsol.org/cgi/viewcvs.cgi/epic5/doc/DCC_REVERSE?rev=1.4
.. _XDCC: http://xa.bi/files/irc/xdcc.3.3.0b.irc
.. _CTCP/2: http://www.invlogic.com/irc/ctcp2_intro.html
.. _DCC Voice: http://www.kvirc.net/doc/cmd_dcc.voice.html
.. _DCC Resume: http://www.mirc.co.uk/help/dccresum.txt
.. _DCC Whiteboard Specification: http://www.visualirc.net/tech-wboard.php
.. _comparison: http://www.kvirc.de/docu/doc_dcc_connection.html

DCC2_ (superseds DCC, CTCP, updated CTCP, CTCP/2)
-------------------------------------------------
A very incomplete (and the website is no longer online) reimplementation of DCC.

* Negotiation_
* Files_

.. _DCC2: http://www.dcc2.org/
.. _Negotiation: http://tools.ietf.org/html/draft-smith-irc-dcc2-negotiation-00
.. _Files: http://www.dcc2.org/files/dcc2/draft-smith-irc-dcc2-files-00.txt

Encryption
==========
* SED_/`CAST5/BLOWFISH/AES`__ `reference implementation`__
* FiSH_

.. _SED: http://cvs.epicsol.org/cgi/viewcvs.cgi/epic5/include/sedcrypt.h?rev=1.12
__ http://cvs.epicsol.org/cgi/viewcvs.cgi/epic5/source/crypt.c?rev=1.42
__ http://cvs.epicsol.org/cgi/viewcvs.cgi/epic5/source/crypto.c?rev=1.17
.. _FiSH: http://cvs.epicsol.org/cgi/viewcvs.cgi/epic5/doc/fish?rev=1.1

Extension Negotiation
=====================

ISUPPORT
--------
* The `005 numeric`_
* `ISupport numeric`_

  * Response code 005; supported by most servers
* `Updated ISupport numeric`_

CAPAB
-----

* `IRC client capabilities negotiation`_
* `Client Capab Proposal`_ (v5)
* `IRC Client Capabilities Extension`_

  * An updated__ version also exists

.. _005 numeric: http://www.irc.org/tech_docs/005.html
.. _ISupport numeric: http://tools.ietf.org/html/draft-brocklesby-irc-isupport-03
.. _Updated ISupport numeric: http://tools.ietf.org/html/draft-hardy-irc-isupport-00

.. _IRC client capabilities negotiation: http://tools.ietf.org/html/draft-baudis-irc-capab-00
.. _Client Capab Proposal: http://www.leeh.co.uk/ircd/client-cap.txt
.. _IRC Client Capabilities Extension: http://tools.ietf.org/html/draft-mitchell-irc-capabilities-01
__ http://www.leeh.co.uk/draft-mitchell-irc-capabilities-02.html

Authentication
==============
* `SASL authentication`_ (PLAIN and BLOWFISH)

  * Note: amlsbGVzAGppbGxlcwBzZXNhbWU= is base64 encoded jilles\0jilles\0sesame
  * Depends on IRC Capabilities
  * `Simple Authentication and Security Layer (SASL)`_

    * `Obsolete RFC`__
  * The `PLAIN Simple Authentication and Security Layer (SASL) Mechanism`_

    * `Obsolete RFC`__
* NickServ
* Auth?
* Ident_

.. _SASL authentication: http://hg.atheme.org/atheme/raw-file/tip/doc/SASL
.. _Simple Authentication and Security Layer (SASL): http://tools.ietf.org/html/rfc4422
__ http://tools.ietf.org/html/rfc2222
.. _PLAIN Simple Authentication and Security Layer (SASL) Mechanism: http://tools.ietf.org/html/rfc4616
__ http://tools.ietf.org/html/rfc2595
.. _Ident: http://tools.ietf.org/html/rfc1413

Services
========
* Anope_
* Atheme
* IRC Services 5
* Sirv
* Epona
* rserv
* srvx
* HybServ2
* KickServices
* `Services compatibility`_

IRC+_
-----
* `PSYC documentation`_
* IRC+ `Conference Control Protocol`_
* IRC+ `Identity Protocol`_
* IRC+ `Subscriptions Protocol`_

.. _Anope: http://www.anope.org/docgen/1.8/
.. _Services compatibility: https://github.com/atheme/charybdis/blob/master/doc/services.txt

.. _IRC+: http://irc-plus.org/en/
.. _PSYC documentation: http://about.psyc.eu/IRCPLUS
.. _Conference Control Protocol: http://www.irc-plus.org/specs/confctrl-draft.html
.. _Identity Protocol: http://www.irc-plus.org/specs/identity-draft.html
.. _Subscriptions Protocol: http://www.irc-plus.org/specs/subscriptions-draft.html

URL Scheme
==========
* `irc:`__
* `irc: and ircs:`__

__ http://tools.ietf.org/html/draft-mirashi-url-irc-01
__ http://tools.ietf.org/html/draft-butcher-irc-url-04

Colors
======
* `ircle colors`_
* `mIRC colors`_
* EPIC_ colors__ (modified mIRC)

.. _ircle colors: http://www.ircle.com/colorfaq.shtml
.. _mIRC colors: http://www.mirc.com/colors.html
.. _EPIC: http://cvs.epicsol.org/cgi/viewcvs.cgi/epic5/doc/color.txt?rev=1.1.1.1
__ http://cvs.epicsol.org/cgi/viewcvs.cgi/epic5/doc/colors?rev=1.1.1.1

Security
========
* STARTTLS_
* `TLS/SSL`_

.. _STARTTLS: http://wiki.inspircd.org/STARTTLS_Documentation
.. _TLS/SSL: http://tools.ietf.org/html/draft-hartmann-default-port-for-irc-via-tls-ssl-09

Other
=====
* `Command Prefix Capability`_ (USERCMDPFX)
* IRCX_ (extends RFC 1459)

  * Microsoft's extension to IRC
* MONITOR_
* WATCH_
* `User Mode +g`_
* `Account-Notify client capability specification`_
* `Target change for Messages`_
* NAMESX_

  * Send all modes of a user
* `Extended Join`_
* TS4_
* Handshake_
* snomasks_
* General `comparison of feature support`__

.. _Command Prefix Capability: http://tools.ietf.org/html/draft-brocklesby-irc-usercmdpfx-02
.. _IRCX: http://tools.ietf.org/html/draft-pfenning-irc-extensions-04
.. _MONITOR: http://hg.atheme.org/charybdis/raw-file/tip/doc/monitor.txt
.. _WATCH: http://www.stack.nl/~jilles/cgi-bin/hgwebdir.cgi/irc-documentation-jilles/raw-file/tip/reference/draft-meglio-irc-watch-00.txt
.. _User Mode +g: http://hg.atheme.org/charybdis/raw-file/tip/doc/modeg.txt
.. _Account-Notify client capability specification: https://github.com/atheme/charybdis/blob/master/doc/account-notify.txt
.. _Target change for Messages: https://github.com/atheme/charybdis/blob/master/doc/tgchange.txt
.. _NAMESX: http://wiki.inspircd.org/Modules/namesx
.. _Extended Join: http://git.atheme.org/charybdis/plain/doc/extended-join.txt
.. _TS4: http://cvs.epicsol.org/cgi/viewcvs.cgi/epic5/doc/TS4?rev=1.1.1.1
.. _Handshake: http://www.stack.nl/~jilles/cgi-bin/hgwebdir.cgi/irc-documentation-jilles/raw-file/tip/reference/draft-meglio-irc-handshake-00.txt
.. _snomasks: http://www.stack.nl/~jilles/cgi-bin/hgwebdir.cgi/irc-documentation-jilles/raw-file/tip/reference/snomasks.txt
__ http://www.alien.net.au/irc/
