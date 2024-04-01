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

- The `50937007739` recipient phone number is used in non-prod Digicel env
- Beneficiary is _Allandy McKinsley_ - `OptIn: true` + `Wallet: true`
- Sending amount is > $1500

### RG Status History

- Cancelled
- Requested to Cancel
- In Payer Review
- Payer Submission
- Submitted
- Pending