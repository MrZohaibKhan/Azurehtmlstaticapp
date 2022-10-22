# Set a custom domain name in Azure static web app
* Buy a custom domain
* Create a static web app in Azure
* Click on add custom domains under setting pane then add a subdomain name and a CNAME record in your DNS managment of your domain registrar.
* Then add your root domain and validate it by adding a TXT record in DNS managment of your domain registrar.
* Add Alias or CNAME record and in the value column add your static web app url.
#### Note: Some registrars like GoDaddy and Google don't support domain records that affect how you configure your apex domain. Consider using Azure DNS with these registrars to set up your apex domain.
* Verify through browser.
