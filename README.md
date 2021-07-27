 # What is this?
 Spoofpoint is a domain monitoring tool that allows you to check a single domain or a list of domains to see if they exist.

 ```bash
git https://github.com/grahamhelton/spoofpoint 
cd spoofpoint
./spoofpoint -i <inputlist> -d <singledomain>
```
![](/example.gif)

# Who is this meant for?
This is meant for people who are tasked with defending an organization from potential phishing attacks via spoofed domains. There are more advanced free tools out there that use python to generate permutations of your domain such as [dnstwist](https://github.com/elceef/dnstwist) but this tool is a super quick and super lightweight to check up on some domains you are worried about.

# Why is this better than <insert big comany's domain monitor tool>
It's probably not, but it does 95% of what those big companies do except it can be done for free in under 5 minutes.
