# Dokku Role for Ansible

Install [Docker](https://www.docker.com/) and [dokku](https://github.com/progrium/dokku/) using official PPAs and perform initial setup for Dokku.

This role was derived from [jnv.dokku-alt](https://github.com/jnv/ansible-role-dokku-alt).

## TODO

- [] Initial pubkey configuration for ACL
- [] Working Vagrant configuration (probably with Landrush)
- [] Travis / Wercker configuration
- [] Use an existing Docker role (?)
- [] Allow automatic reboot on Aufs install

## Example

```yaml
- hosts: servers
  roles:
     - role: jnv.dokku,
       dokku_vhost: 'dokku.docker.dev'
```

## License

MIT
