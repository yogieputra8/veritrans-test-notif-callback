## Veritrans Sample Projects - NodeJS
This is simple project with NodeJS to test make a transaction with Veritrans.  <br />
Projects consists of:<br />
1. chargeTransaction.js to charge the user and send the OrderID and the Amount to VT-Web <br />
2. app.js is to test Notification Callback from Veritrans.<br />


### About veritrans
Payment Gateway Solution for eCommerce merchants in Indonesia to send and receive online payment with credit/debit card, internet and mobile banking.

### Usage
1. `node app.js` <br />
2. Then try to POST to `http://your-server-ip-address:8000` from Veritrans Setting Page. <br />
3. If you are sucess then your console will log out the JSON result from Veritrans and give you Status Code 200 in your Veritrans Page.




