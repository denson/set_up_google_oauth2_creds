# set_up_google_oauth2_creds

The very short version of why you would want to use Oauth2 on your web application is that it allows you to manage users without having to collect and store personal information youself. Google or some other trusted provider handles authenticating that a user is who they claim to be.

This [Digital Ocean article does a pretty good job of summerizing Oauth2](https://www.digitalocean.com/community/tutorials/an-introduction-to-oauth-2). 

In order to generate credentials to use Google as an [Oauth2](https://oauth.net/2/) provider you have to take a few steps:
 
- Verify your domain
- Generate a privacy policy and make if available online.
- Generate Oauth Client ID credentials


You will need to [verify you domain](https://console.developers.google.com/apis/credentials/domainverification) with a [TXT verification record](https://support.google.com/a/answer/183895?hl=en).

You will need a privacy policy page you can easily generate host a [free one](https://www.freeprivacypolicy.com/).

https://console.developers.google.com/apis/credentials

https://www.google.com/webmasters/verification/
