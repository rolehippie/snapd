# snapd

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&amp;logoColor=white)](https://github.com/rolehippie/snapd)
[![General Workflow](https://github.com/rolehippie/snapd/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/snapd/actions/workflows/general.yml)
[![Readme Workflow](https://github.com/rolehippie/snapd/actions/workflows/docs.yml/badge.svg)](https://github.com/rolehippie/snapd/actions/workflows/docs.yml)
[![Galaxy Workflow](https://github.com/rolehippie/snapd/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/snapd/actions/workflows/galaxy.yml)
[![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/snapd)](https://github.com/rolehippie/snapd/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/role-rolehippie.snapd-blue)](https://galaxy.ansible.com/rolehippie/snapd)

Ansible role to primary purge snapd if not required.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [snapd_purge](#snapd_purge)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.10`


## Default Variables

### snapd_purge

Purge all snapd packages and dependencies

#### Default value

```YAML
snapd_purge: true
```

## Discovered Tags

**_snapd_**


## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
