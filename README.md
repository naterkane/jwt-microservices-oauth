


## Request

    POST /oauth/token HTTP/1.1
    Host: localhost:3000
    Content-Type: application/x-www-form-urlencoded
    Cache-Control: no-cache
    Postman-Token: c61e471c-40bd-b7b5-3510-4eda61a95326
    
    grant_type=password&client_id=service1&client_secret=service1secret&username=machineuser&password=machinepass

## Response

    {
      "token_type": "bearer",
      "access_token": "eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJ0aGlzZGVtbyIsInVzZXJJZCI6IjIiLCJleHAiOjE0NjAwNDE5MzcyODAsImlhdCI6MTQ2MDA0MDEzN30.-vtvaHVOAddr8HTYShKMR9XxggWy8MX1DYv46o9_tLo",
      "expires_in": 1800,
      "refresh_token": "eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJ0aGlzZGVtbyIsInVzZXJJZCI6IjIiLCJleHAiOjE0NjEyNDk3MzcyODMsImlhdCI6MTQ2MDA0MDEzN30.4nTdZMBqpnVFtS5Vz7hL-XnQ_0e1XoQh_7wnQPxCd48"
    }