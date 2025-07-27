# sourcemod_linux

The files listed on here are plugins and extensions that are needed among all standard source engine servers. However these plugins have files that are specific to the platform.

### Extensions

### Accelerator
This replaces the default crash handeler which doesn't take in sourcemod into account. Accelerator tis all crashes to a specific steam account (as determined by core.cfg) and updload them to https://crash.limetech.org/ for analyst.
https://forums.alliedmods.net/showthread.php?t=277703

### cURL
A free and easy-to-use client-side URL transfer library, supporting DICT, FILE, FTP, FTPS, GOPHER, HTTP, HTTPS, IMAP, IMAPS, LDAP, LDAPS, POP3, POP3S, RTMP, RTSP, SCP, SFTP, SMTP, SMTPS, TELNET and TFTP. libcurl supports SSL certificates, HTTP POST, HTTP PUT, FTP uploading, HTTP form based upload, proxies, cookies, user+password authentication (Basic, Digest, NTLM, Negotiate, Kerberos), file transfer resume, http proxy tunneling and more! 
https://forums.alliedmods.net/showthread.php?t=152216
https://code.google.com/archive/p/sourcemod-curl-extension/downloads

### STEAM TOOLS:
A library that provides more functionality to plugins. 
https://forums.alliedmods.net/showthread.php?t=236206

### Also a little note about Sourcemod:
A while back Valve patched a vulnerability on the client of multiple Source engine games that disabled the menu feautres. So in order to run commands like !sm_admin, you ave to run cl_showpluginmessages 1 in the client.

### Versions: 
The current versions of Metamod is 2.0.0 #1359-linux and sourcmoed is DEV 1.13.0 #7246-linux. lastest as of 7/27/2025
