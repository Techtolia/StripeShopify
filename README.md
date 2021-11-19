# Get paid for your Shopify orders via Stripe with Alipay, Bancontact, EPS, giropay, iDEAL, Przelewy24, Sofort, WeChat Pay

[Demo ](http://shopifystripe.techtolia.com)--> http://shopifystripe.techtolia.com

With this integration, accept payments for your Shopify Store orders directly at your domain through Stripe with payment methods Alipay, Bancontact, EPS, giropay, iDEAL, Przelewy24, Sofort and WeChat Pay.

#### What is Order and Payment Workflows?
- The customer chooses one of the manual payment methods during the ordering phase through your Shopify store.
- On the order page, the customer is asked to take the order number and go to your payment address.
- The customer comes to your payment address, enters the order number and updates the page. At this stage: The app collects relevant order information from your Shopify account.
- The customer completes the payment. At this stage: The app adds payment and customer information to your Stripe account. 
- The customer is directed back to the application from the payment method page, the customer sees the successful payment screen on the page. At this stage: The app updates the order as paid in your Shopify account.

**[Youtube Preview List](https://www.youtube.com/watch?v=OQZEExsf5aM&list=PLCaaoDXII1ov8Dq5rsGsUiMpA5wc_p6G9)** 

#### What are Payment Methods?
Payment Methods are Alipay, Bancontact, EPS, giropay, iDEAL, Przelewy24, Sofort and WeChat Pay.

For these payment methods, you just need to have a Stripe account and activate your desired payment method from your Stripe control panel. You do not need to make any other application or action.

Payments can be accepted with Przelewy24 in PLN and EUR, with Bancontact, EPS, giropay, iDEAL and SOFORT only in EUR, with Alipay and WeChat Pay CNY and the currencies that map to your country(For example: If your Stripe account country is Germany, you can accept payments in EUR with Alipay and WeChat Pay). Note: If you have a bank account in another currency and would like to create an Alipay payment in that currency, you can contact Stripe support. 

#### What is Smart Url?
- By directing your customer to your checkout.yourdomain.com/Alipay address you can have the page load with Alipay payment method selected.
- By directing your customer to your checkout.yourdomain.com/1001 address, you can have the page load with the order number 1001.
- By directing your customer to your checkout.yourdomain.com/Alipay/1001 address, you can have the page load with Alipay payment method selected and order number 1001 entered.

If the payment for the order number has been made before, the page is updated with a successful screen, the payment button is hidden.

When the user chooses a different payment method or enters a different order number on the application, the url is updated according to that payment method and order number.

#### What is Google reCAPTCHA?
reCAPTCHA is a service that protects your site from spam and abuse. reCAPTCHA v3 helps you detect abusive traffic on your website without user interaction. Instead of showing a CAPTCHA challenge, reCAPTCHA v3 returns a score. reCAPTCHA v2 ("I'm not a robot" Checkbox) requires the user to click a checkbox indicating the user is not a robot.

The application uses combined Google reCAPTCHA v3 and v2. Thus, spam attacks are prevented.

The app first verifies with reCAPTCHA v3 with a score. If the score (can be between 0–1) is not higher than this pass score, the app makes visible reCAPTCHA v2 with the "I'm not a robot" tickbox.

RecaptchaClickLimit: The number is increased each time the buttons are clicked and the page is refreshed. If a user reach the limit, whether the users score is higher than the pass score or not, the app makes visible reCAPTCHA v2 with the "I'm not a robot" tickbox.

#### Quick Start
- Download the source files.
- Activate payment methods on dashboard.stripe.com/account/payments/settings
- Get your Stripe keys on dashboard.stripe.com/apikeys
- Create&Get your reCAPTCHA keys on google.com/recaptcha/admin/create
- Create new private app and Get your API Password on yourusername.myshopify.com/admin/apps/private/new
- Create your manual payments on yourusername.myshopify.com/admin/settings/payments
- Edit the code - Update Keys and Settings.
- Buy a Windows Hosting and Upload the files to the wwwroot folder.
- Create a subdomain (checkout recommended) and match it to the ip information your hosting service provider gave you.

Recommended hosting company: [HostGator](https://partners.hostgator.com/gbqA15). If you want to take advantage of discounted hosting, enter Techtolia in the coupon code field and apply.

If you don't have a domain yet, you can register it via [NameCheap](https://namecheap.pxf.io/BmdkB).

#### Buy a Licence
The single license fee is $750.

If you have completed your purchase through CadeCanyon, please send an e-mail to support@techtolia.com to identify your license information and receive your license key. Do not forget to share your domain address information where you will publish the application, your license is specific to your domain address and cannot be used at any other web address.

For multiple and volume license purchases, please contact us at hello@techtolia.com

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/e34t4qz4yu26hrnv6nz4.png)![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/5xo0c3pg7uy244shw08o.png)![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/aifl50vkxfm9874vjt5u.png)![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/0yx56z7bdxs3r4axse17.png)![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/o2gc3mxjp1h8udmwg3ha.png)![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/yo4en9izj127xifs4dbc.png)![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/jxn74wu02c419nhln64w.png)
