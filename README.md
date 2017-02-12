spotify Ansible role
====================

Installs the Spotify music player client under Linux.

Requirements
------------

Assumes a Debian derivative.

Role Variables
--------------

```yaml
# Will only be used when installing under Debian Stretch.
spotify_libssl_backport_url: "http://security.debian.org/debian-security/pool/updates/main/o/openssl/libssl1.0.0_1.0.1t-1+deb8u6_amd64.deb"
```

Example Playbook
----------------

```yaml
- hosts: workstations
  roles:
    - role: conorsch.spotify
```

License
-------

MIT
