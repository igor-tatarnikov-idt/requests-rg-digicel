## Basic Successful Scenario

- Step 1. Create RG transaction
- Step 2. Release RG transaction

## How To Run?

Make sure you
- Configured private env settings (RG and Digicel auth info)
- Have run the _Get rates & taxes_ request from [digicel-api]() file

Now run requests one by one. The last two will get you the provider transaction info. They are optional

### 3rd Party Notes:

- The `50937007055` recipient phone number is used in non-prod Digicel env
- Beneficiary is _Albert Nadere_ - `OptIn: true` + `Wallet: true`
- Sending amount is > $2.5

```md
Beneficiary look-up returns Full Name: Albert, Last Name: Nadere, Optin: true and Wallet: True
> Remit (Create Token & Execute, or Create Token With Amount, Execute Money Delivery)
> Success 
```

### RG Status History

- Pending
- Submitted
- Payer Submission
- Ready to be Paid
- Paid