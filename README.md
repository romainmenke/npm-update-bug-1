# NPM `update` bug

I would expect `npm update` to not have side effects with node workspaces.
Instead it removes the `name` field from `package-lock.json`
