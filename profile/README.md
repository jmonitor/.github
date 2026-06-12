### About Jmonitor
Jmonitor is a simple and pragmatic monitoring SaaS for PHP applications and web servers. It provides visibility, alerting, and ready-to-use dashboards from common sources in the PHP project stack.

It focus on simple installation and configuration.

- Website: https://jmonitor.io
- Collector packages
  - Any php project: https://github.com/jmonitor/collector
  - Symfony project: https://github.com/jmonitor/jmonitor-bundle

### Principles
- You install a collector package on your app via composer.
- Metrics are collected via a lightweight php script that you periodically run from your environment.
- They are transmitted to Jmonitor.io where they are stored for visualization and alerting.
- You have already made dashboards on your dashboards on your jmonitor.io project's pages.

## Jmonitor may be for you if

- You have a classic PHP application stack.
- You have enough control over your server to install packages via Composer and run a PHP worker (ideally through Supervisor or equivalent).
- You need basic monitoring and alerting.
- You want to get it ready in minutes.
- You don't want to install and maintain a heavy monitoring stack (Prometheus, InfluxDB, Grafana, etc.).

## Jmonitor is not for you if
- You are on a very restricted hosting where you cannot run Composer or background processes.
- You do not use PHP.
- You need a highly granular solution with tracing, logging, etc.
- You want to create yourself all the visualization dashboards and queries.

## Supported stack
- PHP
- Apache
- Nginx
- MySQL
- PostgreSQL
- Redis
- FrankenPHP
- Caddy
- and the server itself (cpu, ram, disk, ...)
