# monitoring-stack
alertmanager, blackbox, cadvisor, grafana, nodeexporter, prometheus, wmi_exporter for windows hosts


## pull, set variables, deploy
```
$ export SLACK_WEBHOOK_URL='https://hooks.slack.com/services/<>/<>/<>'
$ export ROOT_URL=http://grafana:3000
$ export DEFAULT_INSTANCE_NAME=grafana
$ export ADMIN_USER=admin
$ export ADMIN_PASSWORD="beans&rice!"
$ export GF_SECURITY_ADMIN_USER=admin
$ export GF_SECURITY_ADMIN_PASSWORD="beans&rice!"
$ export GF_USERS_ALLOW_SIGN_UP=false
```
or put them in an .env file and source it..
## Bring up containers with docker-compose
```
$ docker-compose up -d
```
## notes
I've only included 2 alert.rules to keep it minimal, service_down and HighCPULoad
