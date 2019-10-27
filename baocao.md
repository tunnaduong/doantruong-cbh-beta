---
layout: default
title: Báo cáo
permalink: /baocao/
bc: active
---
<h1><b>Báo cáo</b></h1>
<script type="text/javascript">
  var oktaSignIn = new OktaSignIn({
    baseUrl: "https://${yourOktaDomain}",
    clientId: "{clientId}",
    authParams: {
      issuer: "https://${yourOktaDomain}/oauth2/default",
      responseType: ['token', 'id_token'],
      display: 'page'
    }
  });
  if (oktaSignIn.token.hasTokensInUrl()) {
    oktaSignIn.token.parseTokensFromUrl(
      function success(tokens) {
        // Save the tokens for later use, e.g. if the page gets refreshed:
        // Add the token to tokenManager to automatically renew the token when needed
        tokens.forEach(token => {
          if (token.idToken) {

            signIn.tokenManager.add('idToken', token);
          }
          if (token.accessToken) {
            signIn.tokenManager.add('accessToken', token);
          }
        });

        // Say hello to the person who just signed in:
        var idToken = signIn.tokenManager.get('idToken');
        console.log('Hello, ' + idToken.claims.email);

        // Remove the tokens from the window location hash
        window.location.hash='';
      },
      function error(err) {
        // handle errors as needed
        console.error(err);
      }
    );
  } else {
    oktaSignIn.session.get(function (res) {
      // Session exists, show logged in state.
      if (res.status === 'ACTIVE') {
        console.log('Welcome back, ' + res.login);
        return;
      }
      // No session, show the login form
      oktaSignIn.renderEl(
        { el: '#okta-login-container' },
        function success(res) {
          // Nothing to do in this case, the widget will automatically redirect
          // the user to Okta for authentication, then back to this page if successful
        },
        function error(err) {
          // handle errors as needed
          console.error(err);
        }
      );
    });
  }
</script>
<p style="color:red">Đăng nhập để tiếp tục!</P>
<div id="okta-login-container"></div>