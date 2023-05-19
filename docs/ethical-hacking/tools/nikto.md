# Nikto

## Description
Nikto is an open source web server scanner written in Perl.

It scans web servers for potentially malicious files and programs,
checks server versions for up-to-dateness and points out known security vulnerabilities

## Examples
``` shell
# simply scan a target
nikto -h example-target.com

# scan a target using https
nikto -h https://example-target.com -ssl

# simply scan an ip address
nikto -h 192.168.178.1

# save scan results into file
nikto -h example-target.com -o results.txt

# scan specific things with -Tuning
nikto -h example-target.com -Tuning <option>

# The tuning options are
0 – File Upload
1 – Interesting File / Seen in logs
2 – Misconfiguration / Default File
3 – Information Disclosure
4 – Injection (XSS/Script/HTML)
5 – Remote File Retrieval – Inside Web Root
6 – Denial of Service
7 – Remote File Retrieval – Server Wide
8 – Command Execution / Remote Shell
9 – SQL Injection
a – Authentication Bypass
b – Software Identification
c – Remote Source Inclusion
x – Reverse Tuning Options (i.e., include all except specified)

# scan only for Misconfiguration and SQL Injection
nikto -h example-target.com -Tuning 29

# scan for all except of Denial of Service
nikto -h example-target.com -Tuning x 6
```
## Additional informations
!!! info "Links"
    - Website: [https://cirt.net/Nikto2](https://cirt.net/Nikto2)
    - Docs: [https://github.com/sullo/nikto/wiki](https://github.com/sullo/nikto/wiki)
    - Source: [https://github.com/sullo/nikto](https://github.com/sullo/nikto)

!!! tip "Alternatives"
    Wapiti