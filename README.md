# Software Engineering at Home Ownership

<img src="https://software-engineering-at-home.github.io/branding/graphics/seath-logo.svg" alt="Software Engineering at Home Logo" height="256" align="right" />

To make the projects and code in the Software Engineering at Home organisation more maintainable.

## Why?

For educational purposes to help people engineer their own software projects from the comfort of their own homes.

## What?

A command and control project to keep software packages up-to-date and in working order.

## How?

See: repos.txt for a list of current projects under the ownership and guidance of this organisation.


## Software Updates

Using [`jumper`](https://github.com/connected-web/jumper); run the following commands to performance maintenance on this org's repos:

Install jumper: 
- `npm i -g github:connected-web/jumper`

Audit repos dependencies: 
- `jumper --strategy audit --repoList ./repos.txt --reference ownership`