## Monorail Playground Repo

This is a minimal repo for users of Monorail to experiment with building user interfaces using the Monorail design system and component library.

## Quick Start

First, go to https://gitlab.com/-/profile/personal_access_tokens and generate a personal access token that has the `read_api` scope. Copy the token to the clipboard. Then, run the following sequence of commands, replacing `<your_token>` with the token that was just generated:

```shell
$ git clone git@gitlab.com:simspace/engineering/ux-engineering/monorail-playground.git
$ yarn config set -H "npmRegistries[\"//gitlab.com/api/v4/projects/35724628/packages/npm/\"].npmAlwaysAuth" "true"
$ yarn config set -H "npmRegistries[\"//gitlab.com/api/v4/projects/35724628/packages/npm/\"].npmAuthToken" "<your_token>"
$ cd monorail-playground
$ yarn
$ yarn dev
```
