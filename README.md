# HTTPS Proxy

This repository contains a [Caddy](https://github.com/caddyserver/caddy) web server deployment to provide TLS termination for all `*.avatour.duckdns.org` domains. This is important as browsers restrict a lot of functionality when running in an insecure context, especially cross-origin.

## Running

You need to provide the file `tls.key` as the private key for TLS termination.

Run: `docker compose up -d`.

## About

This project was written by [Harry Phillips](https://github.com/harryjph).

This project was used as part of the Avatour team's Human Centered Robotics project (Imperial College London, MEng EIE 4th year).
