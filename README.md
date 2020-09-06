# PayPal-Payment-Gateway-in-PHP


![integrate-payment-gateway-paypal-payment-woocommerce-checkout](https://user-images.githubusercontent.com/20369800/92320831-2ce60000-f042-11ea-9393-1c53c815adef.jpeg)




What is Payment Gateway ?
Payment Gateway is a bridge between the credit card holder and Credit card Company to establish a secure connection between them to interchange the data.

This system securely sends your credit card information from the website to the credit card company for processing and then returns with transaction details and response from the bank.

Some of the most Popular Payment gateway examples are: PayPal, Payumoney, Paytm, ccavenue, EBS, Fonepaisa,Atom Paynetz, Citrus, DirecPay etc.
In this tutorial, You will learn
PayPal Payment Gateway integration in PHP
PayPal is an American international e-commerce company which provide a virtual platform for secure and safety money transaction on Internet.
PayPal payment Gateway is a widely used payment gateway used by several web developers for their web pages to establish secure money transfer.

It is the easiest way for web developers to implement a payment system to their Web Applications.
PayPal gateway:-
It uses its own gateway for the transaction known as Pay flow. It is available for both free and paid based on merchant.

Language used in PayPal Payment gateway
Its Front end is created on HTML, CSS, JavaScript and application layer is coded on Java and Node J.S.

How to Integrate ?
Here is a step to step guide for you to how to integrate this to your web applications.
You need to add the following functionalities for a payment gateway.

Prepare the HTML form to collect credit card information.
Create Stripe token to securely transmit card information.
Submit the form with card details.
Verify the card and process charges.
Insert payment details in the database for status to be shown to the user.
It uses two environments i.e. Sandbox and Real-Time.

Sandbox is a self-contained virtual environment which creates a mimic of live environment which allow developers to test their transactions without affecting any live PayPal accounts.

Real-time means when your application will go online. After coding and debugging all you PayPal API in the sandbox move your application to PayPal production environment to go live.

Steps To integrate PayPal Payment Gateway using PHP.
1. Create Sandbox Account
You need to create a Sandbox Account for testing your code. For create your account please visit to this Link.

" https://www.sandbox.paypal.com/cgi-bin/webscr"
2. Create Index.php file

Now you have to create a display output or index file, this file will fetch all the product records from the database and display it onto page.

3. Create a success.php file

Now we have to create a success file for identify your payment when your transaction will be succeeded it will return here. Remember that in case of success transaction the gateway will return you following details.
Item_number
Transaction_ID
AMOUNT
CURRENCY_CODE
PAYMENT_STATUS
So by keeping this in your mind you have to write your code.

4. Create a Cancel.php file

We also need to create a cancel file when the transaction will be cancel then it will redirect here.

5. Going Live

Once everything is working good including all the payment transactions processing flow then you can go live using your PHP code. Just change the sandbox mode to live mode.
