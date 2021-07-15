# google-signin-demo
Google login demo using gapi

## Installation
```javascript
var startApp = function () {
  gapi.load('auth2', function () {
    auth2 = gapi.auth2.init({
      // Change this to your Google ID
      client_id: 'YOUR_GOOGLE_ID.apps.googleusercontent.com',
      cookiepolicy: 'single_host_origin',
    });
	  attachSignin(document.getElementById('btnGoogle'));
	});
};
```
