## Subdomain Enumeration

**Words**: crt.sh, DNS bruteforce (dnsrecon), Sublist3r, ffuf (-w wordlist, -u url, -fs {size} response size)

<pre>-site:www.domain.com site:*.domain.com</pre>
<pre>ffuf -w wordlist -H "Host: FUZZ.domain.com" -u url</pre>
