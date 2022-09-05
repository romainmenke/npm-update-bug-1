# NPM `update` bug

I would expect `npm update` to not have side effects with node workspaces.
Instead it removes the `name` field from `package-lock.json`

see the effects or running `npm update` : https://github.com/romainmenke/npm-update-bug-1/pull/1
