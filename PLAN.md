# SimplePod Plan

## Endpoints

GET /podcast - get all podcasts

POST /podcast - add new podcast

GET /podcast/:podcastid - get specified podcast, inc. description, title, episodes, episode states etc.

DELETE /podcast/:podcastid - delete podcast from library

GET /podcast/:podcastid/:episodeid - get episode status inc. how far through

POST /podcast/:podcastid/:episodeid - push episode status

PUT /podcast/:podcastid/:episodeid - update episode status

POST /podcast/refresh - refresh all podcasts

POST /podcast/refresh/:podcastid - refresh certain podcast

POST /user/signup - create new user

POST /user/signin - sign in as user & get session token

POST /user/signout - revoke user token

DELETE /user - delete current user

## Podcast states
- Listened
- Unlistened
- Archived