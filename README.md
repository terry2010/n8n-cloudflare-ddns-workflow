# n8n-cloudflare-ddns-workflow
n8n cloudflare ddns workflow



## Replace these placeholders:

    YOUR_CLOUDFLARE_API_TOKEN - Your Cloudflare API token
    YOUR_ZONE_ID - Your domain's Zone ID
    YOUR_DOMAIN_NAME - Full domain name to update (e.g., ddns.example.com)

## Get credentials:

    API Token: Cloudflare Dashboard → My Profile → API Tokens → Create Token (needs Zone:DNS:Edit permission)
    Zone ID: Found in domain management page sidebar

## Setup steps:

    Import JSON configuration
    Replace all placeholders (in "Query DNS Record" and "Update DNS Record" nodes)
    Test workflow
    Activate for automatic execution
