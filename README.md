# Matter-most
Auto deploy matter most like a pro with docker- compose and Github Actions.


## Services Deployed
+ Postgres DB
+ PgAdmin4
+ Mattermost app and web


## How it works
push to branch set-up will install docker, docker-compose and start the relevant docker containers.

> Web is accessible on port 80 while pgAdmin is accessible on port 9999
> This can be changed in the docker-compose.yaml



>> Avoid displaying passwords in your repos
