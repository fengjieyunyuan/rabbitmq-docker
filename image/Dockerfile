FROM rabbitmq:3.8-management

COPY rabbitmq_delayed_message_exchange-3.8.9-0199d11c.ez /plugins

RUN rabbitmq-plugins enable --offline rabbitmq_delayed_message_exchange
