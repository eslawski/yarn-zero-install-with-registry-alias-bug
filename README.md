# Renovate Discussion #: 35127


## Current behavior

Renovate correctly groups the `mysql` (gitlabci) and `webpack` (npm) dependencies into the same PR.
However, the yarn cache is NOT updated even though this project is configured to use Yarn zero-installs.

## Expected behavior

Renovate continues to group the dependencies into the same PR, but also updates the Yarn cache.

## Link to the Renovate issue or Discussion

See https://github.com/renovatebot/renovate/discussions/35127
