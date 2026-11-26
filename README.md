<p align="center">
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="assets/wordmark-dark-text.svg">
    <img src="assets/wordmark-light-text.svg" alt="StopTheToken: a community blocklist for AI-generated sites" width="520">
  </picture>
</p>

# StopTheToken
pihole blocklist for ai-generated websites. community-fed -> add to it! 

If you have any reason to believe that a website may be using ai-generation excessively for whatever unlegitimate reason, simply add the website to the blocklist.txt (you may fork and push upstream) and create a pull request explaining your reasoning. 
You may also just create an ISSUE using the Issue template, and I will review and add it on your behalf.

Add to your pi-hole / dns blocker of your choice via:
https://raw.githubusercontent.com/mklemmingen/StopTheToken/main/blocklist.txt

Rules for adding:

    - Each line should contain only one domain.
    
    - Avoid adding comments in the same line as a domain.If needed, you can use a separate file for explanations or place comments in the README.
    
    - The list should not include protocol prefixes (http://, https://) or paths (/page). Only the domain names or subdomains.


