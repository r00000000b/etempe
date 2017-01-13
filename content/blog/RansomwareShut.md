+++
title = "Apple shuts down ransomware attack against Mac users, seeded in BitTorrent"
date = "2016-03-12T13:50:46+02:00"
tags = ["apple", "ransomware", "bittorrent"]
categories = ["white papers"]
banner = "../images/blog/Apple-Gatekeeper975x450.jpg"
author = "Sabine Borgia"
+++

## Apple has managed to quickly block a cyber attack aimed at infecting Mac users with file-encrypting malware known as ransomware that in the past has targeted computers running on Windows.

<div id="ransomware" class="full-width"></div>

Victims of ransomware are asked to pay a fee, usually in bitcoin, to gain access to the decryption key to recover their files.

Security company, Palo Alto Networks, wrote that it found the “KeRanger” ransomware wrapped into Transmission, a free Mac BitTorrent client.

Transmission warned on its website that people who downloaded the 2.90 version of the client “should immediately upgrade to 2.92.”

It was unclear how the attackers managed to upload a tampered version of Transmission to the application’s website, reported PCWorld online.

```
“It’s possible that Transmission’s official website was compromised and the files were replaced by re-compiled malicious versions, but we can’t confirm how this infection occurred,” Palo Alto wrote on its blog.
```

The tainted Transmission version was signed with a legitimate Apple developer’s certificate. If a Mac user’s security settings are set to allow downloads from identified Apple developers, the person may not see a warning from Apple’s Gatekeeper that the application could be dangerous.

Apple has now revoked the certificate. The computing heavyweight has also updated its XProtect antivirus engine.

Once it is installed on a system, KeRanger waits three days before connecting to a remote command-and-control server using the Tor system. It is coded to encrypt more than 300 types of files. The ransom is 1 bitcoin, about US$404.

>> “Ensure your files are regularly backed up and that the backup system is isolated to prevent file infection,” advises Sunil Rathour, CEO of Eagle Eye Systems (EES) Asia.

There are few defences against ransomware. Antivirus programmes often do not catch it since the hackers frequently make modifications to fool security software.

Disturbingly, KeRanger appears to also attempt to encrypt files on Apple’s Time Machine, its consumer backup drive, Palo Alto wrote.