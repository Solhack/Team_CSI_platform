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