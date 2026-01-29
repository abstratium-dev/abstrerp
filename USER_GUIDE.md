# User Manual

## Installation

TODO


### Prerequisites

Before installation, ensure you have:

- **Docker** installed and running
- **MySQL 8.0+** database server
- **Network connectivity** between Docker container and MySQL
- **OpenSSL** for generating JWT keys
- **GitHub account** (if pulling from GitHub Container Registry)
- **nginx** or similar for reverse proxying and terminating TLS

## Initial Onboarding

TODO

## Account and Role Management

This component requires that users can authenticate using an oauth authorization server. That requires that an administrator signs into something like `abstratium-abstrauth` first, to create the oauth2 client. The callback url should be `http://localhost:808x/oauth/callback` and one for the production environment, also ending in `/oauth/callback`. Use the `client_id` and `client_secret` that it provides, to set the values of the environment variables above, so that users can sign in.

## TODO

TODO describe other functionality here.

## Monitoring and Health Checks

TODO
