## Overview

Jasmin is an open source SMS Gateway written in Python and based on Twisted matrix, an event-driven networking engine. It relies on message brokers using AMQP for store-and-forward mechanisms and Redis for in-memory DLR tracking and billing.

## Key Features

- SMPP Client and Server
- HTTP Client and Server
- Console-based configuration with no service restart required
- AMQP broker for store-and-forward and queuing
- Redis for in-memory DLR tracking and billing
- Advanced message routing and filtering: Simple, Roundrobin, Failover, HLR lookup, Leastcost
- Unicode (UTF-8) support for multilingual SMS
- Specialized/binary SMS: mono Ringtones, WAP Push, Vcards
- Concatenated SMS strings (long SMS)
- Telnet connector
- Kubernetes deployment support
- Experimental Heroku deployment

## Deployment

Self-hosted. Installation steps are documented to get Jasmin up and running with a simple SMS sending scenario. Documentation is available at http://docs.jasminsms.com.

## Pricing

Free and open source under the Apache License Version 2.0.