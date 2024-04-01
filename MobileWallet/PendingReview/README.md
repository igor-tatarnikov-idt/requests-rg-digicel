## Pending Review Scenario

- Step 1. Create RG transaction
- Step 2. Release RG transaction
- [Optional] Step 3. Cancel RG transaction 

## How To Run?

Make sure you
- Configured private env settings (RG and Digicel auth info)
- Have run the _Get rates & taxes_ request from [digicel-api](https://github.com/igor-tatarnikov-idt/requests-rg-digicel/blob/a8e5ddf4240c2f69cd1354838682f21a026ffd95/digicel-api.http#L59) file

Now run requests one by one. Feel free to cancel just created transaction

### 3rd Party Notes:

- The `50937007739` recipient phone number is used in non-prod Digicel env
- Beneficiary is _Allandy McKinsley_ - `OptIn: true` + `Wallet: true`
- Sending amount is > $1500

```md
Beneficiary look-up returns Full Name: Allandy, Last Name: McKinsley, Optin: true and Wallet: True,
the Execute call will return a Pending Review status when exceeding the AML Limits (e.g $1500),
hit a saction list, hit an aggregation limit or other AML related rule. 
```

### RG Status History

- Cancelled
- Requested to Cancel
- In Payer Review
- Payer Submission
- Submitted
- Pending