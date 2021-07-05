# Dual package template

Template for `Node.js` and `Deno` dual package project.

## What

This template setting as follow:

- commitizen(gitemoji)
- commitlint
- semantic-release
- husky
- rollup(ES modules, Commonjs)
- browserslist setting
- declaration bundling
- deploy workflow (`npm`, `deno.land`, `nest.land`)
- test workflow

## Prepare

You must replace as follow:

- `${Name}` - Project name
- `${DESCRIPTION}` - Project description
- `${AUTHOR}` - GitHub name

and you must set secret variables to GitHub for publish package registries.

- `NESTAPIKEY` - for nest.land registry
- `NPM_TOKEN` - for npm registry
- `GH_PUBLIC` - GitHub token for changing tag

And if you want to publish to `deno`, you should change webhook.
[more detail](https://deno.land/x)
