# requests-rg-digicel
Test requests for Digicel transaction flows

This repo contains `.http` files used by JetBrains Rider built-in HTTP Client. Files represent transaction lifecycle flows
for Digicel provider integration.

In order to run requests you should update [http-client.private.env.json](https://github.com/igor-tatarnikov-idt/requests-rg-digicel/blob/main/http-client.private.env.json) env file with actual auth data for Digicel and RG.

Digicel non-prod token can be found in AWS Secrets Manager.

For RG auth token I use Swagger API page 'Authorize' button and get data from browser Network tab. Please, let me know,
if there's a more convenient way to achieve it.