### About Jmonitor
Jmonitor is a simple and pragmatic monitoring SaaS for PHP applications and web servers. It provides visibility, alerting, and ready-to-use dashboards from common sources in the PHP project stack.

It focus on simple installation and configuration.

- Website: https://jmonitor.io
- Discussions: https://github.com/orgs/jmonitor/discussions

### Principles
- You install Jmonitor/collector package on your app via composer.
- Metrics are collected via a lightweight php script that you periodically run from your environment.
- They are transmitted to Jmonitor.io where they are stored for visualization and alerting.
- You have already made dashboards on your dashboards on your jmonitor.io project's pages.

## Jmonitor may be for you if

- You have a classic PHP application stack.
- You need basic monitoring and alerting.
- You want to get it ready in minutes.
- You do not need and want to install and maintain a full stack monitoring solution (an aggregator, a time series db, a visualisator, ...).

## Jmonitor is not for you if
- You do not use PHP.
- You need a full and fine-tunable solution with traces, logging, etc
- You want to create yourself all the visualization dashboards and queries.

## Supported stack
- PHP
- Apache
- Nginx
- MySQL
- Redis
- Memcached (planned)
- FrankenPHP
- Caddy (planned)
- and the server itself (cpu, ram, disk, ...)
