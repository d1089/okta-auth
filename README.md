# okta-auth
![Using](https://img.shields.io/badge/using-OktaAuth-blue)
![Using](https://img.shields.io/badge/using-JSP-brightgreen)

1. Using JSP and JS libraries exposed to Okta API
  'The way the Okta widget works is by looking in HTML Local Storage for authentication tokens that determine whether or not there is an active user session. If there’s    no session, the widget knows you aren’t logged in, so it displays a login form.
  Once you’ve entered your user credentials, your login data will be sent to the Okta API service which will securely log you in using the OpenID Connect protocol         (which, FYI, is the recommended way to handle modern web authentication).
  After you’ve been logged in with Okta, the widget will then store your authentication tokens (JSON Web Tokens) in HTML Local Storage for later retrieval.
  If you needed to securely communicate from your web page to a backend API, for example, you could extract your accessToken out of HTML Local Storage and use it to hit
  your API service securely'
  
  ## Demo
  > <img src="https://github.com/d1089/Canva/blob/main/demo/AutomationDemo.gif" width="auto" height="auto" />

2. Using Okta Authentication SDK
   In Progress..
