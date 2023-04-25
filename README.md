# subdomain-takeover-venafi

Vulnerability : Subdomain Takeover

Description :

A subdomain takeover occurs when an attacker gains control over a subdomain of a target domain. Typically, this happens when the subdomain has a canonical name (CNAME) in the Domain Name System (DNS), but no host is providing content for it.

Severity : Medium

Steps to reproduce :

1. While enumerating all subdomains of venafi , I found that one subdomain was pointing to the read.uberflip.com CNAME.

2. And it is throwing an error as mentioned below
