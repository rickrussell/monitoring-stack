# monitoring-stack
alertmanager, cadvisor, grafana, nodeexporter, prometheus, wmi_exporter for hosts


# pull, set slack_webhook_url, deploy
```
$ export SLACK_WEBHOOK_URL='https://hooks.slack.com/services/<>/<>/<>'
$ docker-compose up -d
```
## notes
I've only included 2 alert.rules to keep it minimal, service_down and HighCPULoad
