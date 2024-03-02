# Blackwidow

## Description
BlackWidow is a python based web application spider to gather subdomains, URL's, dynamic parameters, email addresses and phone numbers from a target website. 
This project also includes Inject-X fuzzer to scan dynamic URL's for common OWASP vulnerabilities.

## Examples
``` shell
# crawl example.com with 3 levels of depth
blackwidow -u https://example.com

# crawl the domain example.com with 5 levels of depth with verbose logging enabled
blackwidow -d example.com -l 5 -v y

# crawl the domain example.com with 5 levels of depth using the cookie 'test=test'
blackwidow -d example.com -l 5 -c 'test=test'

# crawl the domain: example.com with 5 levels of depth and fuzz all unique parameters for OWASP vulnerabilities with verbose logging on
blackwidow -d target.com -l 5 -s y -v y

# Fuzz all GET parameters for common OWASP vulnerabilities with verbose logging enabled
injectx.py -u https://test.com/uers.php?user=1&admin=true -v y
```

## Additional informations
!!! info "Links"
    - Website: [https://github.com/1N3/BlackWidow](https://github.com/1N3/BlackWidow)

!!! tip "Alternatives"
    - Burp Spider 
    - HTTrack

