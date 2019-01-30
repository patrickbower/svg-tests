# QuickStart

Opinionated web development project boilerplate

## Setup

Currently this thinking and setup is:

- No NPM packages to install by default.
- HTTPS local host via Caddy.
- Default CSS from Normalise and [Milligram](https://milligram.io/#grids).
- Custom CSS in `./styles.css`.
- Custom JavaScript in `./scripts`.
- Pattern for [native modular ES6](https://pb-journal.netlify.com/article#native-es-modules-5c388b71e60dff2d5d4689e6).

## Install

- Clone the repo
- Change the remote URL `git remote set-url git@github.com:patrickbower/{NEW REPO NAME}.git`
- Verify using `git remote -v`

## To Run

**HTTPS via Caddy on the command-line**

With Caddy installed, run `caddy` within project folder.

**HTTP on the command-line**

Run `php -S 0.0.0.0:1234` within project folder.
