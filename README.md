# fault-tolerant-features-configuration

---

Configuration from https://github.com/emmanuelneri/fault-tolerant-features

#### Webhooks configuration


Add new Webhook in project menu (settings/hooks). 

Configurations: 

- Payload URL: public Config Server URL + /monitor (ex: http://0b52f029.ngrok.io/monitor)
- Content type:  application/json
- Events: Just the push event