# Tornado JSON Web Token example

[**www.codekraft.co**](http://www.codekraft.co)

**Generate a new token:**
http://localhost:8888/auth

**Request test:**
- Using the Postman and a "get method" request on <http://localhost:8888> with this header:
            Authorization:bearer eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzb21lIjoicGF5bG9hZCIsImV4cCI6MTUwMjQ3Mjk5OX0.mTAC5izCCqE71jLWyGQtJRhbj12I79M7qBxbIrieSiE1

- replace token with your generated token

**Requirements:**
> PyJWT 1.5.2
> Tornado 4.51
> Python 3.6

**Codekraft - Paulo Rodrigues**