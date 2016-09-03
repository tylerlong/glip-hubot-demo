# glip-hubot-demo

glip-hubot-demo is a chat bot built on the [Hubot](http://hubot.github.com/) framework with [hubot-glip](https://github.com/tylerlong/hubot-glip) adapter.


## Running glip-hubot-demo

You can start glip-hubot-demo locally by running:

    % HUBOT_GLIP_EMAIL=your@email.com \
      HUBOT_GLIP_PASSWORD=your-password \
      HUBOT_ZENDESK_USER=your@email.com \
      HUBOT_ZENDESK_PASSWORD=your-password \
      HUBOT_ZENDESK_SUBDOMAIN=your-subdomain \
      SF_INSTANCE_URL = salesforce-url \
      SF_CONSUMER_KEY = salesforce-key \
      SF_CONSUMER_SECRET = salesforce-secret \
      SF_USERNAME = salesforce-username \
      SF_PASSWORD = salesforce-password \
      ./bin/hubot -a glip -n hubot
