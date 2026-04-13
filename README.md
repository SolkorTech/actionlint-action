# actionlint-action

This action runs [`actionlint`](https://github.com/rhysd/actionlint) for all workflows in a repository.

> [!IMPORTANT]
> This action uses a container to run `actionlint`, so it is *highly* recommended to use a Linux runner like `ubuntu-latest`!

## Usage

```yaml
- name: Checkout
  uses: actions/checkout@v6

- name: Check workflow files
  uses: SolkorTech/actionlint-action@v1
```
