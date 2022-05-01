Project demoing usage of JWT with Spring boot

POST request to: http://localhost:8080/authenticate with JSON payload

{
"username": "foo",
"password": "foo"
}

Then GET to: http://localhost:8080/hello with JWT returned from POST using Authorization header
prefixed with Bearer e.g.

Bearer eyJhb.eyJ.mBUxPG