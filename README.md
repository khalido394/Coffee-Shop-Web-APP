# Coffee Shop Full Stack

## Full Stack Nano - IAM Final Project

Udacity has decided to open a new digitally enabled cafe for students to order drinks, socialize, and study hard. But they need help setting up their menu experience.

You have been called on to demonstrate your newly learned skills to create a full stack drink menu application. The application must:

1) Display graphics representing the ratios of ingredients in each drink.
2) Allow public users to view drink names and graphics.
3) Allow the shop baristas to see the recipe information.
4) Allow the shop managers to create new drinks and edit existing drinks.

## Final test!
```shell
curl --request POST \
  --url 'https://khalido394.auth0.com/oauth/token' \
  --header 'content-type: application/x-www-form-urlencoded' \
  --data grant_type=client_credentials \
  --data 'client_id=doG6Max3sqYRV8vVEQCF24Xbp2LMiTdM' \
  --data client_secret=18R-WrLWOwE0O2EhmnlGhZn2WagaKdExcWCCHMYJJdlow7qwyD1hg6gfo_G1R4Pj \
  --data audience=Coffee-shop
```
Result:
```

{"access_token":"eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCIsImtpZCI6IjFDZEU0UkRQbjhHdXpoLXZXdVJfcCJ9.eyJpc3MiOiJodHRwczovL2toYWxpZG8zOTQuYXV0aDAuY29tLyIsInN1YiI6ImRvRzZNYXgzc3FZUlY4dlZFUUNGMjRYYnAyTE1pVGRNQGNsaWVudHMiLCJhdWQiOiJDb2ZmZWUtc2hvcCIsImlhdCI6MTU5MTE3OTgwOCwiZXhwIjoxNTkxMjY2MjA4LCJhenAiOiJkb0c2TWF4M3NxWVJWOHZWRVFDRjI0WGJwMkxNaVRkTSIsInNjb3BlIjoiZ2V0OmRyaW5rcyBwb3N0OmRyaW5rcyBwYXRjaDpkcmlua3MgZ2V0OmRyaW5rcy1kZXRhaWwgZGVsZXRlOmRyaW5rcyIsImd0eSI6ImNsaWVudC1jcmVkZW50aWFscyIsInBlcm1pc3Npb25zIjpbImdldDpkcmlua3MiLCJwb3N0OmRyaW5rcyIsInBhdGNoOmRyaW5rcyIsImdldDpkcmlua3MtZGV0YWlsIiwiZGVsZXRlOmRyaW5rcyJdfQ.AoBMPsJzjo6tuS8uFhOxM99HL4t-aGnuWZ8vBhmSTyfLTCxKfOY6fjJjujzBSnEAhLiioTQ-953Fvkn0uCCqrRcT5Mcwicha0YoNHrXHq4kWFBXRgFOfQ6B7N-3FQD9YgjhzeOSesmh-vVq5Rfs9X4ENqCmjrHbenJmuwUrYftPxghGAyhhY_BWhclrm3Es2R15o8OA9NNCpClEwXW-1lST5czOmn30cFHkaYDUzQah-rg5Opz7r7PXzuDm4bfWpyTjbcDBwNiiI-1Wr59BQPAvVSzqpx9mlE8Bt9x93R7OLdsGbopNNXRVzuuBp5YuQ_w3-0R9IYnz8y9nd6HjWoQ","scope":"get:drinks post:drinks patch:drinks get:drinks-detail delete:drinks","expires_in":86400,"token_type":"Bearer"}

```

