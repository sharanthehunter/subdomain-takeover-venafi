# subdomain-takeover-venafi

Vulnerability : Subdomain Takeover

Description :

A subdomain takeover occurs when an attacker gains control over a subdomain of a target domain. Typically, this happens when the subdomain has a canonical name (CNAME) in the Domain Name System (DNS), but no host is providing content for it.

Severity : Medium

Steps to reproduce :

1. While enumerating all subdomains of venafi , I found that one subdomain was pointing to the read.uberflip.com CNAME.

2. And it is throwing an error as mentioned below


![image](https://user-images.githubusercontent.com/84071887/234296627-59950c1c-c1c7-4f52-a3da-2cb2ba7d2e06.png)



#Non-Hub domain

The URL you have accessed does not provide a hub. Please check the URL and try again.

3. which means if it is not added it can be added to any account, as Uberflip documentation suggests that after your subdomain is pointing to their CNAME which is read.uberflip.com, your subdomain should be added to your account so it shows the URL you chose for your hub.

4. An attacker can easily take over this subdomain by simply adding this domain name to their uberflip account.

5.  As I couldn't sign up on their website to test due to signup problems, I just wanted your confirmation whether this subdomain is added in an uberflip account or not.

6.  If not then claim it otherwise any one can add or claim this to their Uberflip account.

Impact : Subdomain takeover



#REPLY FROM VENAFI :

Thank you for notifying us about this issue. Venafi's security teams are already aware of this problem which has been resolved.


-Venafi Security
