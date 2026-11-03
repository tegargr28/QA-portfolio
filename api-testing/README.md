# API testing: Restful-Booker

API docs: https://restful-booker.herokuapp.com/apidoc/index.html
Tool: Postman

I'm working through the endpoints one by one. The plan:

| Endpoint | Method | What I check | Done |
| -------- | ------ | ------------ | ---- |
| /booking | GET | status 200, list of booking IDs | no |
| /booking/{id} | GET | status 200, fields look right | no |
| /booking | POST | status 200, response matches what I sent | no |
| /auth | POST | returns a token for valid login | no |
| /booking/{id} | PUT | updates data when token is sent | no |
| /booking/{id} | DELETE | deletes with token, rejected without | no |

Negative cases I want to cover:
- PUT and DELETE without a token
- booking ID that doesn't exist
- POST with missing fields

Next steps: export the collection to this folder, publish the Postman docs, and try running it with Newman.
