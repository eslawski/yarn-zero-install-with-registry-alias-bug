# minimal-reproduction-template

First, read the [Renovate minimal reproduction instructions](https://github.com/renovatebot/renovate/blob/main/docs/development/minimal-reproductions.md).

Then replace the current `h1` with the Renovate Issue/Discussion number.

## Current behavior

Renovate correctly groups the `mysql` (gitlabci) and `webpack` (npm) dependencies into the same PR.
However, the yarn cache is NOT updated even though this project is configured to use Yarn zero-installs.

## Expected behavior

Renovate continues to group the dependencies into the same PR, but also updates the Yarn cache.

## Link to the Renovate issue or Discussion

Put your link to the Renovate issue or Discussion here.
