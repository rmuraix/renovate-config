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

Some features use [Hatena presets](https://github.com/hatena/renovate-config)

### PR creation

- Waiting 3 days for patch and minor updates
- schedule: "after 8am before 5pm on Monday"
- Adding `auto merge` label to the PRs that are auto-merged
- Grouping jest monorepo packages and ts-jest
- Grouping various libraries used for Android app development, mainly based on Maven groupId
- Grouping ComposeOptions and kotlin

### Auto marge

The following are auto-merged

- Patch updates
- [DefinitelyTyped](https://github.com/DefinitelyTyped/DefinitelyTyped)'s minor updates
- ESlint related minor updates

## References

[Shareable Config Presets - Renovate Docs](https://docs.renovatebot.com/config-presets/)  
[Configuration Options- Renovate Docs](https://docs.renovatebot.com/configuration-options/)
