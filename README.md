# TODO

## Preview/Staging

https://fitsearchwebapp.azurewebsites.net/

List of test credit cards:
https://docs.adyen.com/development-resources/test-cards/test-card-numbers#american-express-amex

For example you can take first one:

| Card Number        | Issuing Country | Expiry Date | CID  |
|--------------------|-----------------|-------------|------|
| 3700 0000 0000 002 | NL              | 03/2030     | 7373 |


## Small tasks

- [ ] auto approval of schedule request after 1 hour (quick)
- [ ] cancel schedule (2 hours)
- [ ] add links to email: approval link, view links, decline link (3 hours)
- [ ] filtering (1 day)
- [ ] sending email (moving functionality from working system) (1 hour)
- [ ] fetching correct firstname/lastname during facebook login (1 hour)
- [ ] registering
- [ ] try to configure Azure AD B2C login not to use popup window
- [ ] cache server response data in client app to avoid page loading delay, when switching between pages (service details/schedule/order/etc)

## Bigger tasks

- [ ] integrating with Google Calendar (2 days)
- [X] integrating with Payment system (1 week)
- [ ] integrating design (1 week)
- [ ] setup server (one day)
      - setup domain email
      - create PayAsYouGo catalog/account in Azure Cloud for production system
      - register Merchant account in Adyen for production system
      - bind domains to Azure cloud
      - upload applications to production cloud
      - Social login:
      
        - register accounts / configure social logins in social networks
        - add/configure social login providers in Azure AD B2C

## Business application

- [ ] pages for business account: create service, approve schedule, edit profile (1 day)

## Good to have (can be implemented later)

- [ ] system to solve problems with emails, which wasn't sent for some reason
