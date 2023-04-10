# Nginx Proxy setup

This is a simple [nginx-proxy] setup for docker-compose.

It is intended for my personal use, and might not be mantained or updated.

This repository might be deleted or taken private at any time. Please fork it if you want to use it.

[nginx-proxy]: https://github.com/nginx-proxy/nginx-proxy

## Usage

A bunch of notes.

- I am mounting the config files from the host. Other projects may copy their own configuration
  in the same folder, and they will be loaded by nginx. There must be a better way but for now this is all I've got.
- For localhost development, you have to download the certificates from the nginx-proxy container and add them to `/certs` in `/scripts` there is a script for that. You might have to adjust `/certs` permissions
