# workflows-common
Reusable GitHub Actions workflows for the digabi GitHub org

## Actions

- `actions/setup-ci-certs`: Installs mkcert on Ubuntu runners, installs the provided CA into trust stores, writes `cert.pem`/`key.pem`/`chain.pem`/`fullchain.pem`/`domain.txt`, and ensures the hostname exists in `/etc/hosts`.
