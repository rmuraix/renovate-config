# renovate-config

[![License](https://img.shields.io/github/license/rmuraix/renovate-config)](./LICENSE)  
A shareable config preset for Renovate

## Usage

```json
{
  "extends": ["github>rmuraix/renovate-config"]
}
```

## features

### PR creation

- Waiting 3 days
- schedule: "after 8am before 5pm on Monday"
- Adding `auto merge` label to the PRs that are auto-merged
- Grouping various packages

### Auto marge

The following are auto-merged

- Patch updates
- [DefinitelyTyped](https://github.com/DefinitelyTyped/DefinitelyTyped)'s minor updates
- ESlint related minor updates

## Contributing

Your contribution is always welcome. Please read [Contributing Guide](./.github/CONTRIBUTING.md).

## References

[Shareable Config Presets - Renovate Docs](https://docs.renovatebot.com/config-presets/)  
[Configuration Options- Renovate Docs](https://docs.renovatebot.com/configuration-options/)
