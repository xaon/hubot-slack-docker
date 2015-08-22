# hubot-slack-docker

## How to use

Go to [https://you-company.slack.com/services/new](https://you-company.slack.com/services/new) and configure the Hubot integration.

Then:

```sh
docker build -t oct/hubot
docker run  -it -e "HUBOT_SLACK_TOKEN=xoxb-fdsadfsafafdsa" oct/hubot
```
The hubot script folder can be mounted using:
```sh
docker run -it -v /your/path/to/scripts:/root/scripts hubot
```
