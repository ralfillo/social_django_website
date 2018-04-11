# Django Blog 

## Setup for "secrets.json"
The motivation of this setup is to keep secret values away from your public repository without using environment variables.

In this case it's used to maintain the privacy of the email login details.

In this setup, the "secrets.json" file is allocated in the project's root directory.

### Example for a Gmail account and Facebook social auth
    {
      "EMAIL_HOST": "smtp.gmail.com",
      "EMAIL_HOST_USER": "this_is_not_a_real_email@gmail.com",
      "EMAIL_HOST_PASSWORD": "not_a_real_password_1234",
      "EMAIL_PORT": 587,
      "SECRET_KEY": "(/kdsjf4wr@noug6-##bmjsajdfñklajz%fdsfqo5!4fe8hxzp%a3+cp",
      "SOCIAL_AUTH_FACEBOOK_KEY": "9834293749264938",
      "SOCIAL_AUTH_FACEBOOK_SECRET": "sdf798f6sd786a9370gd7fs20e"
    }