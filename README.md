# cloudflare-ddns
Script for updating IPv4 and IPv6 IPs using the Cloudflare v4 API.

### How to use
Fill in the fields at the top of the script to authenticate with Cloudflare. Scoped API Token is strongly recommended. On the IPv6 script you also need to name the interface where the IPv6 address is assigned. 

Automate the script using a simple Cron job to keep the IPs updated. 

### Note
The API-key used for updating DNS records will have full access to the whole DNS-zone. I would suggest using a throwaway domain and point to this domain using CNAME-records. This will minimise the impact ever so slightly should one of your boxes be compromised.  


### Credit 
https://github.com/K0p1-Git/cloudflare-ddns-updater
