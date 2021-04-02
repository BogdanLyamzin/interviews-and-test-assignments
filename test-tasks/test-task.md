Create new react project 
Make a login form UI 
User email validation 
Authorize user 
Create functionality for auto refreshing access token (access token lifetime 1h)

User authorization works via oAuth2 standard. To authorize send a request to Access token endpoint. As a result server gives you response with access token and refresh token. The lifetime of access token is 1 hour, so you should send request to Refresh Token endpoint  to getting new access token by using refresh token.

BASE API DOMAIN: https://candidate-api.testly.space

Client: wcs
Secret: 3A37A940F361D2148CCCF2D5C7C6B605
Username: candidate@aily.team
Password: e,theyc33

Access token endpoint: [POST] /oauth/token
Headers: 
	Authorization: Basic <HASHEDSTR(<Client>:<Secret>)>
Data: 
	username: “<username>”
	grant_type: “password”
	password: “<password>”


Refresh Token endpoint: [POST] /oauth/token
Data: 
	grant_type: “refresh_token”
	refresh_token: “<refresh_token>”


Useful related links:
	HASHING WITH BTOA - https://www.w3schools.com/jsref/met_win_btoa.asp
