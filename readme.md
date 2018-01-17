# Vend Postman

A Postman Collection repository for Vend API Endpoints. 

- [Official API Docs](https://docs.vendhq.com/)
- [Postman Collection Docs](https://documenter.getpostman.com/view/1806395/vend-public-api/7Ln9hhN#10c9d566-55dc-d9f3-1f2e-d164098fbc0c)

## How to use?

The Postman Collection file is a JSON containing all information about each request.
This Collection is using Postman Environment Variables, so all you have to do is create an Environment in Postman and register the Postman variables, which are:

- domainprefix
- token

There are other variables which have purposely been left as placeholders which you will need to set depending on the request. To learn more about Postman variables: https://www.getpostman.com/docs/environments

## How do I generate a Personal Token? 

[Personal Tokens](https://support.vendhq.com/hc/en-us/articles/204886420-Personal-Tokens) are a simplified method of acquiring an access token. In order to retrieve or create a Token, log in to your Vend account and go to https://{domainprefix}.vendhq.com/setup/personal-tokens