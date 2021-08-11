# Revolut2Accointing


Bash wrapper for AWK scripts to convert Revolut transactions into Accointing-compatible format

The main purpuse of this script is to allow users to import their exported transactions from Revolut into their Accointing.com account

## How to use the scripts

### revolutTransactions2Accointing.sh

* Ask Revolut support to export all transactions to CSV on your behalf and provide a secure link to download them using the phone number and PIN associated to the Revolut account

* Execute the relevant script providing the exported file from Revolut as input 

Example:

```
bash revolutTransactions2Accointing.sh transactions_history.csv 
```

The above command will create the output file `revolutTransactionsExport_Accointing.csv` that can be manually imported into the target Accointing.com account

## Limitations

The script currently support deposits only, I have not had the need to import withdrawals yet and for this reason I have not seen how withdrawals from Revolut look alike# Revolut2Accointing
