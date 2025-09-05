# Jmonitor

Simple, pragmatic monitoring for PHP applications and web servers. Get visibility, alerting, and ready‑to‑use dashboards with minimal setup.

- Website: https://jmonitor.io
- Discussions: https://github.com/orgs/jmonitor/discussions

## Principles
- Install the `jmonitor/collector` package in your app via Composer.
- A lightweight PHP script collects metrics on a schedule (e.g., cron, systemd timer, task scheduler).
- Metrics are sent to Jmonitor.io, stored, visualized, and used for alerting.
- Prebuilt dashboards are available on your Jmonitor.io project pages.

## Features
- Ready‑to‑use dashboards for common PHP stacks
- Essential metrics and alerting out of the box
- Lightweight collector with simple configuration
- No infrastructure to operate (SaaS)

## Quick start
1. Require the collector in your project:
   - Using Composer: `composer require jmonitor/collector`
2. Configure your project key and desired integrations in the collector config.
3. Schedule the collector execution (every 1–5 minutes recommended) from your environment.
4. Open your project on https://jmonitor.io to see dashboards and set alerts.

## Jmonitor may be for you if
- You use a classic PHP application stack.
- You need basic monitoring and alerting.
- You want it running in minutes.
- You do not want to install and maintain a full monitoring stack (aggregator, time‑series DB, visualizer, ...).

## Jmonitor is not for you if
- You do not use PHP.
- You require a fully customizable, full‑stack observability platform with traces, logs, etc.
- You want to build all dashboards and queries yourself from scratch.

## Supported stack
- PHP
- Apache
- Nginx
- MySQL
- Redis
- FrankenPHP
- Server basics (CPU, RAM, disk, ...)
- Memcached (planned)
- Caddy (planned)

## Support
- Questions and discussions: https://github.com/orgs/jmonitor/discussions
- Report issues: https://github.com/jmonitor (see relevant repository)

## License
Proprietary service; see https://jmonitor.io for terms.
