# cscli
Simple tool to remotely manage CrowdSec LAPI built with Rust

The idea around this tool is to create a basic implementation of cscli aimed at LAPI management (Alerts / Decisions).

The current CSCLI tool provided by CrowdSec is aimed at being a feature complete management of everything (alerts / decisions / parsers / scenarios), however, users may only want to run some commands without having the need to install the whole CrowdSec package.

v1 todos:

- [ ] Support CRUD base operations
    - [ ] Alerts
    - [ ] Decisions
- [ ] Authentication types
    - [ ] JWT
    - [ ] Certificates
- [ ] LAPI register


