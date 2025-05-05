# Enabling flakes
Make sure to have the following line in `~/.config/nix/nix.conf`:
`experimental-feature = nix-command flakes`

# Create a new flake
`nix flake init`
or with a template:
`nix flake init -t <url>#<template>`
For more information on templates run `nix help flake init`.

# direnv
For best integration with `direnv` use `nix-direnv` (see [README](https://github.com/nix-community/nix-direnv?tab=readme-ov-file#flakes-support)).

