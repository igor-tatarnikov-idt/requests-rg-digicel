## Pending Review Scenario

- Step 1. Create RG transaction
- Step 2. Release RG transaction
- [Optional] Step 3. Cancel RG transaction 

## How To Run?

Make sure you
- Configured private env settings (RG and Digicel auth info)
- Have run the _Get rates & taxes_ request from [digicel-api]() file

Now run requests one by one. Feel free to cancel just created transaction

### 3rd Party Notes:

- The `50934483776` recipient phone number is used in non-prod Digicel env
- Beneficiary is _Albert Nadere_ - `OptIn: true` + `Wallet: true`
- Sending amount is $40

```md
Beneficairy look-up returns Full Name: Albert,Last Name: Nadere, Optin: true and Wallet: True,
and send amount example is $1000 >Pending Review or Pending Receiver> return error code when exceeding the Wallet Limits.
Error shall say: (RECEIVE_AMOUNT_EXCEEDS_WHAT_THE_RECEIVER_CAN_RECEIVE)
```

### RG Status History

- Cancelled
- Requested to Cancel
- In Payer Review
- Payer Submission
- Submitted
- Pending