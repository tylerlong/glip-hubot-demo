# glip-hubot-demo

glip-hubot-demo is a chat bot built on the [Hubot][hubot] framework with [hubot-glip](https://github.com/tylerlong/hubot-glip) adapter.


## Running glip-hubot-demo

You can start glip-hubot-demo locally by running:

    % HUBOT_GLIP_EMAIL=your@email.com \
      HUBOT_GLIP_PASSWORD=your-password \
      HUBOT_ZENDESK_USER=your@email.com \
      HUBOT_ZENDESK_PASSWORD=your-password \
      HUBOT_ZENDESK_SUBDOMAIN=your-subdomain \
      ./bin/hubot -a glip -n hubot
