# snapd

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/snapd) [![Build Status](https://img.shields.io/drone/build/rolehippie/snapd?logo=drone)](https://cloud.drone.io/rolehippie/snapd) [![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/snapd)](https://github.com/rolehippie/snapd/blob/master/LICENSE) 

Ansible role to primary purge snapd if not required. 

## Sponsor 

[![Proact Deutschland GmbH](https://proact.eu/wp-content/uploads/2020/03/proact-logo.png)](https://proact.eu) 

Building and improving this Ansible role have been sponsored by my employer **Proact Deutschland GmbH**.

## Table of content

* [Default Variables](#default-variables)
  * [snapd_purge](#snapd_purge)
* [Dependencies](#dependencies)
* [License](#license)
* [Author](#author)

---

## Default Variables

### snapd_purge

Purge all snapd packages and dependencies

#### Default value

```YAML
snapd_purge: true
```

## Dependencies

* None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
