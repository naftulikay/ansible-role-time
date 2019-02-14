# ansible-role-time [![Build Status][travis.svg]][travis]

Installs and configures time synchronization on a machine using `ntpd` or `systemd-timesyncd`. This role is targeted at
providing a time _client_ to keep time in sync with other servers; as opposed to installing and configuring `ntpd` as an
actual time server for others to use.

Available on Ansible Galaxy at [`naftulikay.time`][galaxy].

## License

Licensed at your discretion under either:

 - [Apache Software License, Version 2.0](./LICENSE-APACHE)
 - [MIT License](./LICENSE-MIT)

 [galaxy]: https://galaxy.ansible.com/naftulikay/time/
 [travis.svg]: https://travis-ci.org/naftulikay/ansible-role-time.svg?branch=master
 [travis]: https://travis-ci.org/naftulikay/ansible-role-time
