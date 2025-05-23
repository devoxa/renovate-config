<!-- Title -->
<h1 align="center">
  renovate-config
</h1>

<!-- Description -->
<h4 align="center">
  The <a href="https://docs.renovatebot.com/config-presets/">shareable configuration</a>
  for <a href="https://www.whitesourcesoftware.com/free-developer-tools/renovate/">Renovate</a> used in all Devoxa projects
</h4>

<!-- Badges -->
<p align="center">
  <a href="https://github.com/devoxa/renovate-config/actions?query=branch%3Amaster+workflow%3A%22Continuous+Integration%22">
    <img
      src="https://img.shields.io/github/actions/workflow/status/devoxa/renovate-config/push.yml?branch=master&style=flat-square"
      alt="Build Status"
    />
  </a>
</p>

<!-- Quicklinks -->
<p align="center">
  <a href="#installation">Installation</a> •
  <a href="#extending">Extending</a> •
  <a href="#contributors">Contributors</a> •
  <a href="#license">License</a>
</p>

<br>

## Installation

Create a file in `.github/renovate.json` with the following content:

```json
{
  "extends": ["github>devoxa/renovate-config"]
}
```

## Extending

This configuration is not intended to be changed, but if you have a setup where modification is
required, it is possible. See the
[Renovate docs](https://docs.renovatebot.com/configuration-options/) for more details.

## Contributors

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://www.david-reess.de"><img src="https://avatars3.githubusercontent.com/u/4615516?v=4" width="75px;" alt=""/><br /><sub><b>David Reeß</b></sub></a><br /><a href="https://github.com/devoxa/renovate-config/commits?author=queicherius" title="Code">💻</a> <a href="https://github.com/devoxa/renovate-config/commits?author=queicherius" title="Documentation">📖</a> <a href="https://github.com/devoxa/renovate-config/commits?author=queicherius" title="Tests">⚠️</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors)
specification. Contributions of any kind welcome!

## License

MIT
