---
title: "Password 2FA"
date: 2024-02-23T11:01:48+01:00
draft: true
tags: ["security", "IT"]
---


## Password Keepass Auto-Type Sequences
### Liste of Services

The standard sequence for login mask is: ` {USERNAME}{TAB}{PASSWORD}{ENTER}`.
But there are a couple of service, requiring a different sequence. Here is my list of online services, with the respective sequence.  

| Service       | URL                                                    | Sequence                                                    | Updated    |
| ------------- | ------------------------------------------------------ | ----------------------------------------------------------- | ---------- |
| Mailbox.org   | https://login.mailbox.org/                             | ` {USERNAME}{ENTER}{DELAY 1000}{TAB}{PASSWORD}{ENTER}`      | 24.11.2023 |
| Amazon.de     | https://www.amazon.de/                                 | ` {USERNAME}{ENTER}{DELAY 2000}{PASSWORD}{ENTER}`           | 24.11.2023 |
| Humble Bundle | https://www.humblebundle.com/login                     | `{USERNAME}{TAB}{PASSWORD}{ENTER}{DELAY 1000}{TOTP}{ENTER}` | 25.11.2023 |
| Google        | https://accounts.google.com/                           | ` {USERNAME}{ENTER}{DELAY 3000}{PASSWORD}{ENTER}`           | 26.11.2023 |
| Komoot        | https://account.komoot.com/signin?reason=homepage-main | ` {USERNAME}{ENTER}{DELAY 1000}{PASSWORD}{ENTER}`           | 03.12.2023 |
| EPIC          | https://www.epicgames.com/id/login                     | `{USERNAME}{TAB}{PASSWORD}{ENTER}{DELAY 1000}{TOTP}{ENTER}` | 03.12.2023 |
| Paypal        | https://www.paypal.com/                                | `{USERNAME}{TAB}{PASSWORD}{ENTER}{DELAY 1000}{TOTP}{ENTER}` | 04.12.2023 |
| Diskstation   | {ip}:5001                                              | `{USERNAME}{TAB}{PASSWORD}{ENTER}{DELAY 1000}{TOTP}{ENTER}` | 06.12.2023 |
| Sparkasse     |                                                        | `{USERNAME}{ENTER}{DELAY 1000}{PASSWORD}{ENTER}`            | 25.02.2024 |

### References

- [Keepass Auto-Types Description](https://keepass.info/help/base/autotype.html)

- [KeePassXC UserGuide for auto_type_sequences](https://keepassxc.org/docs/KeePassXC_UserGuide#_configure_auto_type_sequences)

- [Repo with KeePass-AutoType-Sequences](https://github.com/wikijm/KeePass-AutoType-Sequences)