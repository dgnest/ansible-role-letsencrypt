# Ansible Role ansible-role-letsencrypt

<span class="badges" align="center">
[![Build Status](https://travis-ci.org/dgnest/ansible-role-letsencrypt.svg)](https://travis-ci.org/dgnest/ansible-role-letsencrypt)
[![Stories in Ready](https://badge.waffle.io/dgnest/ansible-role-letsencrypt.svg?label=ready&title=Ready)](http://waffle.io/dgnest/ansible-role-letsencrypt)
[![GitHub issues](https://img.shields.io/github/issues/dgnest/ansible-role-letsencrypt.svg)](https://github.com/dgnest/ansible-role-letsencrypt/issues)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](LICENSE)
</span>


This Ansible Role infuses antigravity, you are warned

Install it with the following command:

```bash
$ ansible-galaxy install dgnest.letsencrypt
```

Requirements
------------

None

## Role Variables

Here is the list of all variables and their default values:

| Name                                    | Default                       | Description                                   |
|:----------------------------------------|:------------------------------|:----------------------------------------------|


## Dependencies

none

## Example Playbook

See the [examples](./examples/) directory.

To run this playbook with default settings, create a basic playbook like this:

```yaml
- hosts: servers
  roles:
    - dgnest.letsencrypt
```

## License

MIT

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Credits

Made with :heart: ️:coffee:️ and :pizza: by [dgnest][link-company].
- [All Contributors][link-contributors]

---

<!-- Other -->

[link-company]: https://github.com/dgnest
[link-author]: https://github.com/luismayta
[link-contributors]: AUTHORS