Target 178.79.174.156

Scans
port information
PORT     STATE    SERVICE      VERSION
80/tcp   open     http         Apache httpd 2.4.38 ((Debian))
|_http-server-header: Apache/2.4.38 (Debian)
|_http-title: Apache2 Debian Default Page: It works
139/tcp  filtered netbios-ssn
445/tcp  filtered microsoft-ds
631/tcp  filtered ipp
2222/tcp open     ssh          OpenSSH 6.0p1 Debian 4+deb7u2 (protocol 2.0)

Stealth scans
PORT     STATE    SERVICE      VERSION
80/tcp   open     http         Apache httpd 2.4.38 ((Debian))
|_http-server-header: Apache/2.4.38 (Debian)
|_http-title: Apache2 Debian Default Page: It works
139/tcp  filtered netbios-ssn
445/tcp  filtered microsoft-ds
631/tcp  filtered ipp
2222/tcp open     ssh          OpenSSH 6.0p1 Debian 4+deb7u2 (protocol 2.0)

 PORT      STATE    SERVICE      REASON      VERSION
80/tcp    filtered http         no-response
2222/tcp  filtered EtherNetIP-1 no-response
22333/tcp filtered unknown      no-response

Vulnerabilities 
PORT    STATE    SERVICE      VERSION
80/tcp  open     http         Apache httpd 2.4.38 ((Debian))
|_clamav-exec: ERROR: Script execution failed (use -d to debug)
|_http-csrf: Couldn't find any CSRF vulnerabilities.
|_http-dombased-xss: Couldn't find any DOM based XSS.
|_http-server-header: Apache/2.4.38 (Debian)
|_http-stored-xss: Couldn't find any stored XSS vulnerabilities.
| vulners: 
|   cpe:/a:apache:http_server:2.4.38: 
|       CVE-2020-11984  7.5     https://vulners.com/cve/CVE-2020-11984
|       CVE-2019-0211   7.2     https://vulners.com/cve/CVE-2019-0211
|       CVE-2019-10082  6.4     https://vulners.com/cve/CVE-2019-10082
|       CVE-2019-10097  6.0     https://vulners.com/cve/CVE-2019-10097
|       CVE-2019-0217   6.0     https://vulners.com/cve/CVE-2019-0217
|       CVE-2019-0215   6.0     https://vulners.com/cve/CVE-2019-0215
|       CVE-2020-1927   5.8     https://vulners.com/cve/CVE-2020-1927
|       CVE-2019-10098  5.8     https://vulners.com/cve/CVE-2019-10098
|       CVE-2020-9490   5.0     https://vulners.com/cve/CVE-2020-9490
|       CVE-2020-1934   5.0     https://vulners.com/cve/CVE-2020-1934
|       CVE-2019-10081  5.0     https://vulners.com/cve/CVE-2019-10081
|       CVE-2019-0220   5.0     https://vulners.com/cve/CVE-2019-0220
|       CVE-2019-0196   5.0     https://vulners.com/cve/CVE-2019-0196
|       CVE-2019-0197   4.9     https://vulners.com/cve/CVE-2019-0197
|       CVE-2020-11993  4.3     https://vulners.com/cve/CVE-2020-11993
|_      CVE-2019-10092  4.3     https://vulners.com/cve/CVE-2019-10092
139/tcp filtered netbios-ssn
445/tcp filtered microsoft-ds
631/tcp filtered ipp

Public key creation to leverage public key at port "2222"
ssh-keygen -t rsa 
ssh-copy-id -p root@178.79.174.156

ssh -p 2222 root@178.79.174.156
password:Target 178.79.174.156

Scans
port information
PORT     STATE    SERVICE      VERSION
80/tcp   open     http         Apache httpd 2.4.38 ((Debian))
|_http-server-header: Apache/2.4.38 (Debian)
|_http-title: Apache2 Debian Default Page: It works
139/tcp  filtered netbios-ssn
445/tcp  filtered microsoft-ds
631/tcp  filtered ipp
2222/tcp open     ssh          OpenSSH 6.0p1 Debian 4+deb7u2 (protocol 2.0)

Stealth scans
PORT     STATE    SERVICE      VERSION
80/tcp   open     http         Apache httpd 2.4.38 ((Debian))
|_http-server-header: Apache/2.4.38 (Debian)
|_http-title: Apache2 Debian Default Page: It works
139/tcp  filtered netbios-ssn
445/tcp  filtered microsoft-ds
631/tcp  filtered ipp
2222/tcp open     ssh          OpenSSH 6.0p1 Debian 4+deb7u2 (protocol 2.0)

 PORT      STATE    SERVICE      REASON      VERSION
80/tcp    filtered http         no-response
2222/tcp  filtered EtherNetIP-1 no-response
22333/tcp filtered unknown      no-response

Vulnerabilities 
PORT    STATE    SERVICE      VERSION
80/tcp  open     http         Apache httpd 2.4.38 ((Debian))
|_clamav-exec: ERROR: Script execution failed (use -d to debug)
|_http-csrf: Couldn't find any CSRF vulnerabilities.
|_http-dombased-xss: Couldn't find any DOM based XSS.
|_http-server-header: Apache/2.4.38 (Debian)
|_http-stored-xss: Couldn't find any stored XSS vulnerabilities.
| vulners: 
|   cpe:/a:apache:http_server:2.4.38: 
|       CVE-2020-11984  7.5     https://vulners.com/cve/CVE-2020-11984
|       CVE-2019-0211   7.2     https://vulners.com/cve/CVE-2019-0211
|       CVE-2019-10082  6.4     https://vulners.com/cve/CVE-2019-10082
|       CVE-2019-10097  6.0     https://vulners.com/cve/CVE-2019-10097
|       CVE-2019-0217   6.0     https://vulners.com/cve/CVE-2019-0217
|       CVE-2019-0215   6.0     https://vulners.com/cve/CVE-2019-0215
|       CVE-2020-1927   5.8     https://vulners.com/cve/CVE-2020-1927
|       CVE-2019-10098  5.8     https://vulners.com/cve/CVE-2019-10098
|       CVE-2020-9490   5.0     https://vulners.com/cve/CVE-2020-9490
|       CVE-2020-1934   5.0     https://vulners.com/cve/CVE-2020-1934
|       CVE-2019-10081  5.0     https://vulners.com/cve/CVE-2019-10081
|       CVE-2019-0220   5.0     https://vulners.com/cve/CVE-2019-0220
|       CVE-2019-0196   5.0     https://vulners.com/cve/CVE-2019-0196
|       CVE-2019-0197   4.9     https://vulners.com/cve/CVE-2019-0197
|       CVE-2020-11993  4.3     https://vulners.com/cve/CVE-2020-11993
|_      CVE-2019-10092  4.3     https://vulners.com/cve/CVE-2019-10092
139/tcp filtered netbios-ssn
445/tcp filtered microsoft-ds
631/tcp filtered ipp

Social Engineering on Nithen

Public key creation to leverage public key at port "2222"
ssh-keygen -t rsa 
ssh-copy-id -p root@178.79.174.156

ssh -p 2222 root@178.79.174.156
password: "your public key password"

"open says you"


ssh -p 22333 sshackctf1@178.79.174.156
sshackctf1@178.79.174.156's password: 
Linux li311-156 4.19.0-10-amd64 #1 SMP Debian 4.19.132-1 (2020-07-24) x86_64

The programs included with the Debian GNU/Linux system are free software;
the exact distribution terms for each program are described in the
individual files in /usr/share/doc/*/copyright.

Debian GNU/Linux comes with ABSOLUTELY NO WARRANTY, to the extent
permitted by applicable law.
Last login: Tue Aug 25 19:59:02 2020 from 197.185.107.130

  _________                 .___     
 /   _____/ ____   ____   __| _/____    _______________________________ 
 \_____  \ /    \ /  _ \ / __ |/ __ \   ___  __ )__  ____/__  __/__    |
 /        \   |  (  <_> ) /_/ \  ___/   __  __  |_  __/  __  /  __  /| |
/_______  /___|  /\____/\____ |\___  >  _  /_/ /_  /___  _  /   _  ___ |
        \/     \/            \/    \/   /_____/ /_____/  /_/    /_/  |_|
          --------------------------------------


root@li311-156ls -la
*** Unknown syntax: ls -la
root@li311-156sudo -i
*** Unknown syntax: sudo -i
root@li311-156echo
*** Unknown syntax: echo
root@li311-156echo Sol
*** Unknown syntax: echo Sol
root@li311-156mkdir Solomon 
*** Unknown syntax: mkdir Solomon
root@li311-156dir
*** Unknown syntax: dir
root@li311-156cat
*** Unknown syntax: cat
root@li311-156help

Documented commands (type help <topic>):
========================================
exit  help  show  shutdown

root@li311-156show
Usage: show manual|license|tutorial|faq
root@li311-156show manual 
This is the default welcome page used to test the correct operation of the Apach
e2 server after installation on Debian systems. If you can read this page, it me
ans that the Apache HTTP server installed at this site is working properly. You 
should replace this file (located at /var/www/html/index.html) before continuing
 to operate your HTTP server.
root@li311-156show tutorial
Introduction
The Apache HTTP server is the most widely-used web server in the world. It provi
des many powerful features including dynamically loadable modules, robust media 
support, and extensive integration with other popular software.

In this guide, we’ll explain how to install an Apache web server on your Debian 
10 server.

