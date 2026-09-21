# Backend auth

The API issues a JWT on login or register. Protected routes expect `Authorization: Token <jwt>`. The frontend restores that token on load. There is no OAuth and no Hub session cookie on this API.
