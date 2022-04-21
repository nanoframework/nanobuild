[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![#yourfirstpr](https://img.shields.io/badge/first--timers--only-friendly-blue.svg)](https://github.com/nanoframework/Home/blob/main/CONTRIBUTING.md) [![Discord](https://img.shields.io/discord/478725473862549535.svg?logo=discord&logoColor=white&label=Discord&color=7289DA)](https://discord.gg/gCyBu8T)

![nanoFramework logo](https://raw.githubusercontent.com/nanoframework/Home/main/resources/logo/nanoFramework-repo-logo.png)

-----

## GitHub Action that installs .NET **nanoFramework** build components

This action installs .NET **nanoFramework** build components required to build projects and solutions in GitHub Actions.

It doesn't require any configurations, simply installs the components.

>Note: in order to run properly this action requires setting up the GitHub token. There are numerous ways of doing this.
On the examples below it's being set on the action itself. If that's done elsewhere before the action runs, there is no need to do it again.

## Example usage

Install .NET **nanoFramework** build components as part of a GitHub Action building a project/solution.

```yaml
- uses: nanoframework/nanobuild@v1
  env:
    GITHUB_TOKEN: ${{ github.token }}
```

## Feedback and documentation

For documentation, providing feedback, issues and finding out how to contribute please refer to the [Home repo](https://github.com/nanoframework/Home).

Join our Discord community [here](https://discord.gg/gCyBu8T).

## Credits

The list of contributors to this project can be found at [CONTRIBUTORS](https://github.com/nanoframework/Home/blob/main/CONTRIBUTORS.md).

## License

The **nanoFramework** Class Libraries are licensed under the [MIT license](LICENSE.md).

## Code of Conduct

This project has adopted the code of conduct defined by the Contributor Covenant to clarify expected behaviour in our community.
For more information see the [.NET Foundation Code of Conduct](https://dotnetfoundation.org/code-of-conduct).

### .NET Foundation

This project is supported by the [.NET Foundation](https://dotnetfoundation.org).
