# Uplyft Connect Demo
This project provides a demo on how to integrate an Uplyft member log-in on your platform.

The member log-in works for every whitelabel program available at Uplyft.

## Demo
Check out the live [demo](https://uplyft-dev.github.io/connect-demo/).

## Configuration
| Param  | Description |
|---|---|
| CONNECT_URL | Will be provided by Uplyft. |
| CONNECT_CLIENT_ID | Will be provided by Uplyft. |
| RESPONSE_TYPE | Set to 'token' for OAuth implicit code grant. |
| SCOPE |  Can be any combination of 'openid', 'email', 'phone', 'profile'. Depending on the further token usage. |
| REDIRECT_URI | Configure the URL that should be called after authentication, needs to be registered at Uplyft. |
| STATE | Custom value that can be set by the client. Will be included in the redirect. Can be used to prevent [CSRF](https://en.wikipedia.org/wiki/Cross-site_request_forgery). |
| TYPE | Can either be 'login' or 'signup'.  Determines the initial flow of the authenticaion UI. |
