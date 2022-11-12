notes:
# QuickNginx
## What is it going to be
App to create docker compose file that runs nginx docker container with two arguments - ports - to be redirected

## Main features so far
- 2 ports as arguments
- http only so far
- to access app from different machine in the same local network
- just for development - this is a really important assumption - never use on production

## Usage
example call:
`qnx 4000 8080` - redirect port 4000 to app running on port 8080

## Future features
- switch to use http or https
- ssl certificate
- redirect many at one
- define hostname
- websockets to make signalR usable
