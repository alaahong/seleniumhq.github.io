---
title: "Two Factor Authentication"
weight: 1
---

{{% notice info %}}
<i class="fas fa-language"></i> Diese Seite wird von Englisch 
auf Deutsch übersetzt. Sprichst Du Deutsch? Hilf uns die Seite 
zu übersetzen indem Du uns einen Pull Reqeust schickst!
{{% /notice %}}

Two Factor Authentication (2FA) is an authorization 
mechanism where a One Time Password (OTP) is generated using "Authenticator" 
mobile apps such as "Google Authenticator", "Microsoft Authenticator" 
etc., or by SMS, e-mail to authenticate. Automating this seamlessly 
and consistently is a big challenge in Selenium. There are some ways 
to automate this process. But that will be another layer on top of our 
Selenium tests and not as secure. So, you should avoid automating 2FA.

There are few options to get around 2FA checks:

* Disable 2FA for certain Users in the test environment, so that you can 
use those user credentials in the automation.
* Disable 2FA in your test environment.
* Disable 2FA if you login from certain IPs. That way we can configure our 
test machine IPs to avoid this.
