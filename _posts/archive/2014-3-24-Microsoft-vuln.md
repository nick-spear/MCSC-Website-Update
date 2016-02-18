---
layout: post
title:  "Microsoft announced (3/24/2014) an in the wild exploit of Word v. 2003,
2007, 2010, 2011, 2013."
date:   2014-3-24 21:19:48
categories: archive

---
Because of the way Outlook and Word interact on the windows operating
system this should be considered an outlook vulnerability as well but
that portion of the exploit has not been seen in the wild.

The basic outline of the attack is to take advantage of a problem with
ow word handles RTF (Rich Text Format) files (*.rtf) to execute code
that will install a backdoor and then other malware will follow.
Microsoft is working on the issue.

This is a "nasty" exploit because it affects many systems and uses the
rtf format that is often used to exchange documents between systems.

Microsoft's technical note can be found <a href="https://technet.microsoft.com/en-us/security/advisory/2953095">here.</a>

For a greater technical discussion click <a href="https://threatpost.com/word-zero-day-attacks-use-complex-chain-of-exploits/">here.</a>