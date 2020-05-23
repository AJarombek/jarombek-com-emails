# aws-lambda-emails

> *Formerly jarombek-com-emails*

### Overview

AWS Lambda functions for sending emails.  Used by my `saintsxctf.com` and `jarombek.com` 
applications.

### Commands

```bash
# Create an AWS Lambda ZIP file.
rm welcomeEmail.zip
zip -r welcomeEmail.zip .
```

### Files

| Filename         | Description                                                         |
|------------------|---------------------------------------------------------------------|
| `dist`           | AWS Lambda `zip` files ready for distribution.                      |
| `jarombek-com`   | Emails for the `jarombek.com` application.                          |
| `saints-xctf`    | Emails for the `SaintsXCTF` application.                            |
| `send-email`     | Reusable module for sending emails on AWS.                          |

### Resources

**Outdated Resources**

1. [NodeJS Gmail OAuth2](http://nodemailer.blogspot.com/)
2. [NodeMailer Auth](https://nodemailer.com/smtp/oauth2/#example-5)
3. [NodeMailer Refresh Token](https://stackoverflow.com/questions/24098461/nodemailer-gmail-what-exactly-is-a-refresh-token-and-how-do-i-get-one)

**Current Resources**

1. [Get SecretsManager Secret](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SecretsManager.html#getSecretValue-property)
