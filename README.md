# AF_UNIX-stream-socket_YubiKey-ripoff

A PKCS#11 security token is stored on USB flash drive and when plugged in and allowed access, an AF_UNIX stream socket will be established between a process spawned by the USB key and a decryption process of a LUKS encrypted device via `systemd-cryptenroll`.

This is just a rough outline from about 30 minutes of research. But fuck Yubico and their YubiKeys. $25 to $1000 for a USB drive that you can't use for anything else. I mean, they are open-source, but they are still about that moneys. So, I'm going to give it a go before I give in and buy one of their products.

This is really just a project to create a removable drive that unlocks my encrypted DAS. I don't actually have anything against Yubico. But,let's see how this goes before forking over the $50.
