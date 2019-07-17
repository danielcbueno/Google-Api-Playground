# Google-Sheets-Basics-Access
This repository will show you how to access a worksheet in the google worksheet service.

Important highlights for you to consider:

- First of all, go to the [Google APIs page](https://developers.google.com/sheets/api/quickstart/dotnet) to generate credentials and get your password.
- Store the credentials.json file with the structure similar to the one below, but with your access data.
```JSON
{
  "installed": {
    "client_id": "YoutClientId",
    "project_id": "YourProjectId",
    "auth_uri": "https://accounts.google.com/o/oauth2/auth",
    "token_uri": "https://oauth2.googleapis.com/token",
    "auth_provider_x509_cert_url": "https://www.googleapis.com/oauth2/v1/certs",
    "client_secret": "YourClientSecret",
    "redirect_uris": ["urn:ietf:wg:oauth:2.0:oob", "http://localhost"]
  }
}
```
- In the tokens.json file, you will only enter your api access password on it, (Do not enter your password for your google account).

If in doubt, please contact us.
