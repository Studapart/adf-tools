# adf-tools (Studapart fork)

Studapart-maintained fork of [DamienHarper/adf-tools](https://github.com/DamienHarper/adf-tools) **1.2.1**.
Public PHP API stays `DH\Adf\` so existing converters keep working.

[![Latest Stable Version](https://poser.pugx.org/studapart/adf-tools/v/stable)](https://packagist.org/packages/studapart/adf-tools)
[![adf-tools CI](https://github.com/Studapart/adf-tools/actions/workflows/ci-1.x.yml/badge.svg)](https://github.com/Studapart/adf-tools/actions/workflows/ci-1.x.yml)
[![License](https://poser.pugx.org/studapart/adf-tools/license)](https://packagist.org/packages/studapart/adf-tools)

Atlassian Document Format PHP Tools

The purpose of `adf-tools` is to provide an easy way to build, parse and export documents based on Atlassian Document Format.

## Installation

Once the package is on Packagist:

```bash
composer require studapart/adf-tools:^1.2.2
```

Until Packagist publish, consume the GitHub VCS repository:

```json
{
  "repositories": [
    {
      "type": "vcs",
      "url": "https://github.com/Studapart/adf-tools.git"
    }
  ],
  "require": {
    "studapart/adf-tools": "^1.2.2"
  }
}
```

`composer.json` includes `"replace": { "damienharper/adf-tools": "self.version" }` so a later switch from upstream does not install two copies.

## Documentation
- Documentation of this library can be found [here](doc/index.md).
- [Official Atlassian Document Format](https://developer.atlassian.com/cloud/jira/platform/apis/document/structure/)
- [Atlassian Document Format JSON Schema](https://unpkg.com/@atlaskit/adf-schema@24.0.0/dist/json-schema/v1/full.json)


## Version Information
| Version | Status                      | Requirements | Badges                                                                                                                                                                                                                                                                                                                                 |
|:--------|:----------------------------|:-------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1.x     | Active development :rocket: | PHP >= 7.4   | [![adf-tools 1.x CI](https://github.com/Studapart/adf-tools/actions/workflows/ci-1.x.yml/badge.svg)](https://github.com/Studapart/adf-tools/actions/workflows/ci-1.x.yml) |

CI for this line runs on **PHP 8.4**. Production Composer constraint remains `php: >=7.4`.

Changelog: [CHANGELOG.md](CHANGELOG.md) and [GitHub releases](https://github.com/Studapart/adf-tools/releases).


## Contributing
`adf-tools` is an open source project. Contributions made by the community are welcome.
Send us your ideas, code reviews, pull requests and feature requests to help us improve this project.

Do not forget to provide unit tests when contributing to this project.
To do so, follow instructions in this dedicated [README](doc/contributing.md)


## Credits
- Original author: [Damien Harper](https://github.com/DamienHarper) (`DamienHarper/adf-tools`)
- Maintained by [Studapart](https://github.com/Studapart)
- Thanks to [all contributors](https://github.com/Studapart/adf-tools/graphs/contributors)
- Special thanks to [JetBrains](https://www.jetbrains.com/?from=adf-tools) for their *Licenses for Open Source Development*


## License
`adf-tools` is free to use and is licensed under the [MIT license](LICENSE).
Damien Harper's copyright from upstream 1.2.1 is preserved.
