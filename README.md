# poisonTheWell
a collection of scripts for ruining the databases of phishing attackers


Ever gotten one of these? "There has been suspicious activity on your {paypal|ebay|wellsfargo} account. Please log in and update your information at https://myInformationSecurity/PayPal"

The goal of this project is to visit those websites, and fill their database with  false but feasible credentials inclugin fake generated names, email addresses, SSNs, credit card numbers, DOB etc. The goal is to make their databases unusable by increading the noise and decreasing signal-to-noise ratio and making the database of stored credentials useless. 

## Data rate / SNR

Hoping to get 100 per second entries generated, which would allow for 8.6 million entries per day. SNR = 1.86e-7 or about ‬-67 dB.

(At one entry per second, we could still produce 86400 entries per day. The expected max signal rate for a successful phishing attack may be 100 per minute or 1.6 entries / sec. SNR in this  case would be 1.6/2.6 or 0.64 or about -2 dB.) 

## As a service

In the future, we may offer this as a service to the companies involved in these phishing attacks, as a matter to protect their customers.
