# nginx-http-auth-request-module-example

This setup starts two containers, `app` listenting on port 8010 with secured endpoints and `auth-backend` which serves different responses for `ngx_http_auth_request_module`.

http://localhost:8010/private1/ will authorize the request successfully against the auth-backend

http://localhost:8010/private2/ won't get an 200 OK during the auth process and returns therefore 401 unauthorized as status.
