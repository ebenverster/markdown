Hi there team X,

Thank you for choosing to integrate with wiGroup. Here are some things you will need to get you started. If you have any questions, please feel free to ask anyone from our team. We will go ahead and setup a Skype group where we can all communicate should you have any questions.

<h3>Documentation and guides:</h3>

We've included the following documents and guides to the email to get you started.

* Suggested user journey (including API calls) presentation attached.

* POS integration and API documentation attached, or online here:

	`http://rad3.wigroup.co/wigroup/integration/pos/#wiplatform-overview`

<h3>API</h3>

As soon as you are comfortable with our API, you can test it out using the SOAP UI project  attached. It includes examples of the *transactionRequest* and *transactionAdvice* calls.

* POS Provider API endpoint:

	`http://rad2.wigroup.co:8080/wigroup-te-za-rad/PosProviderWS?wsdl`
	
* API credentials for QA:

	````JSON
"apiId": "POS_54"
"apiPassword": "de3e88a1e0754d89fb5c399e6af99038a55bfe50"
"storeId": "1050"
````

<h3>wiCodes</h3>

Generate wiCodes to transact with here:

* **Payment**: Download the _FlickPay_ application for Android here:
		
	`https://www.dropbox.com/sh/7mrd9xhyzt7xwv2/AABR-K_j2a6TuUI_lR5VHsoea?dl=0`
		
	It will allow you to make payments using a dummy account, which should be pre-loaded when you install the application. Don't worry, this is not real money :)
		
* **Coupon/Voucher**: You can access this website:

	`http://qa.wigroup.co/wigroup/mobi/Cambridge/`
		
	The site issues from the campaigns in the table below.
		
   | Campaign ID  | 	Campaign |	Type | SKU 1 | SKU 2|
	------------ | ---------- | ----- | ---- | ----- |
	| 2992  | Combo Coupon |	Coupon | 1111 | 2222 |
	| 2991  | Single SKU Coupon 1 | Coupon | 123456789 | NA |
	| 2992  | Multi SKU Coupon |	Coupon | 1234 | 56789 |
	| 2990  | Percentage Value Voucher 1 | Voucher | NA | NA |
	| 2987  | Rand Value Voucher 1 | Voucher | NA | NA |
		
* **Loyalty**: Use the same website:
	
	`http://qa.wigroup.co/wigroup/mobi/Cambridge/`
		
	You can issue a zero value coupon/voucher from the campaigns in the following table.
		
	| Campaign ID  | 	Campaign |	Type | SKU 1 | SKU 2|
	------------ | ---------- | ----- | ---- | ----- |
	| 4800  | R0 Value Coupon |	Coupon | 1234 | NA |
	| 4777  | R0 Value Voucher | Voucher | NA | NA |

Remember to add the applicable SKU information when making your API calls.

Kind regards,

> add your signature here