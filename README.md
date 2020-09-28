# MailSenderAPI_NodeJS

This ia an API in NodeJS using express to send emails using the Gmail REST API.

The application -

- Obtains a Gmail user's credentials using OAuth 2.0. The OAuth 2.0 process is initiated by an API call to the server.
- Stores the obtained credentials in a file
- There is API endpoint to execute send email using the credentials previously stored
