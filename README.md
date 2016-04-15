# Ansible Role: Memcached

Installs and configures the Memcached.

## Requirements

None.

## Role Variables

### `defaults/main.yml`

* `memcached_port: 11211`
* `memcached_listen_ip: 127.0.0.1`
* `memcached_maxconn: 1024`
* `memcached_cachesize: 64`
* `memcached_log_enable: false`
* `memcached_log_file: "/var/log/memcached.log"`
* `memcached_log_verbosity: ""`

## Dependencies

None.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - name: Install Memcached.
      hosts: servers
      roles:
        - role: ansible-role-memcached
          memcached_log_enable: True

## License

MIT / BSD

## Author Information

z
