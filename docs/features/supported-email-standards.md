---
title: Supported Email Standards
---

## Supported Email Standards
We're happy to support the most up-to-date standards for email security, fetching, and especially privacy. We require SSL be enabled on user's IMAP4/POP3/SMTP servers when sending or receiving email.

unicorn supports the following:
- mailboxes hosted on Hosted Exchange/Microsoft 365 for Business (as of toffeeOS Dev 1.6.4)
- mailboxes hosted on Exchange Server 2016, 2019
  - In protest of Microsoft moving Exchange Server to a subscription model (which we do not agree with), we will not be supporting Exchange Server 2022 at this time. Please use IMAP to interact with this release.
- IMAP4 w/ SSL (recommended)
- POP3 w/ SSL (not recommended)
- SMTP w/ SSL

*in unicorn 1.6.4, we began recommending IMAP4 (with SSL) connections to fetch mail from email servers. We may enforce the use of IMAP4 in future versions of unicorn, including the final public release of toffeeOS 1.
