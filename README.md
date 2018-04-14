![seclists.png](https://danielmiessler.com/images/seclists-long.png "seclists.png")

# About

SecLists is the security tester's companion. It's a collection of multiple types of lists used during security assessments, collected in one place. List types include usernames, passwords, URLs, sensitive data patterns, fuzzing payloads, web shells, and many more. The goal is to enable a security tester to pull this repo onto a new testing box and have access to every type of list that may be needed.

This project is maintained by [Daniel Miessler](http://www.danielmiessler.com/ "Daniel Miessler") and [Jason Haddix](http://www.securityaegis.com "Jason Haddix").

## Contributing

If you have any ideas for things we should include, please use one of the following methods to submit them:

1. Send us pull requests
2. Create an issue in the project (right side)
3. Send us links through the issues feature, and we'll parse and incorporate them
3. Email daniel.miessler@owasp.org or jason.haddix@owasp.org with content to add

Significant effort is made to give attribution for these lists whenever possible, and if you are a list owner or know who the original author/curator is, please let us know so we can give proper credit.

### Attribution

- Adam Muntner and for the FuzzDB content, including all authors from the FuzzDB project (https://github.com/fuzzdb-project/fuzzdb)
- Ron Bowes of SkullSecurity for collaborating and including all his lists here (https://wiki.skullsecurity.org/Passwords)
- Clarkson University for their research that led to the Clarkson list
- All the authors listed in the XSS with context doc, which was found on pastebin and added to by us
- Ferruh Mavitina for the beginnings of the LFI Fuzz list
- Kevin Johnson for laudnaum shells (https://sourceforge.net/projects/laudanum/)
- RSnake for fierce hostname list
- Charlie Campbell for Spanish word list, numerous other contributions
- Rob Fuller for the IZMY list
- Mark Burnett for the 10 million passwords list
- @shipCod3 for an SSH user/pass list
- Steve Crapo for doing splitting work on a number of large lists
- Thanks to Blessen Thomas for recommending Mario's/cure53's XSS vectors
- Thanks to Danny Chrastil for submitting an anonymous JSON fuzzing list
- Many thanks to @geekspeed, @EricSB, @lukebeer, @patrickmollohan, @g0tmi1k, @albinowax, and @kurobeats for submitting via pull requests
- Special thanks to @shipcod3 for MANY contributions!
- Thanks to Samar Dhwoj Acharya for allowing his Github Dorks content to be included!
- Thanks to Liam Somerville for the excellent list of default passwords
- Great thanks to Michael Henriksen for allowing us to include his Gitrob project's signatures
- Honored to have @Brutelogic's brilliant XSS Cheatsheet added to the Fuzzing section!
- 0xsobky's Ultimate XSS Polyglot!
- @otih for bruteforce collected username and password lists
- @govolution for betterdefaultpasslist (https://github.com/govolution/betterdefaultpasslist)
- Max Woolf (@minimaxir) for **big-list-of-naughty-strings** (https://github.com/minimaxir/big-list-of-naughty-strings) [`/Fuzzing/big-list-of-naughty-strings.txt`]
- Ian Gallagher (@craSH) for **http-request-headers** [`/Miscellaneous/http-request-headers/`]
- Arvind Doraiswamy (@arvinddoraiswamy) for **numeric-fields-only** [`/Fuzzing/numeric_fields_only.txt`]
- @badibouzouk for **Domino Hunter** (https://sourceforge.net/projects/dominohunter/) [`/Discovery/Web-Content/Domino-Hunter/`]
- @coldfusion39 for **domi-owned** (https://github.com/coldfusion39/domi-owned) [`/Discovery/Web-Content/domino-*-coldfusion39.txt`]

This project stays great because of care and love from the community, and we will never forget that. If you know of a contribution that is not listed above, please let us know…

## Licensing

This project is licensed under the MIT license.

![MIT License](https://danielmiessler.com/images/mitlicense.png)

—

<sup>NOTE: Downloading this repository is likely to cause a false-positive alarm by your antivirus or antimalware software, the filepath should be whitelisted. There is nothing in Seclists or FuzzDB that can harm your computer as-is, however it's not recommended to store these files on a server or other important system due to the risk of local file include attacks.</sup>
