## Receiver Not Found Scenario

- Step 1. Create RG transaction
- Step 2. Release RG transaction

## How To Run?

Make sure you
- Configured private env settings (RG and Digicel auth info)
- Have run the _Get rates & taxes_ request from [digicel-api](https://github.com/igor-tatarnikov-idt/requests-rg-digicel/blob/a8e5ddf4240c2f69cd1354838682f21a026ffd95/digicel-api.http#L59) file

Now run requests one by one. The last two will get you the provider transaction info. They are optional

### 3rd Party Notes:

- The `50937007217` recipient phone number is used in non-prod Digicel env

```md
Beneficairy Look-Up returns error code: 1103, message: receiver not ready to receive. Receiver does not have a MonCash wallet registered.
```

### RG Status History

- Payer Submission
- Ready to be Paid
- Paid