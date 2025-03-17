# fish-asdf

`fish-asdf` is a [fisher](https://github.com/jorgebucaran/fisher) plugin for the [fish shell](https://fishshell.com/) that provides the necessary configuration to use [asdf](https://asdf-vm.com/) seamlessly. It ensures that `asdf` works correctly in the fish shell without adding any extra functionality or unnecessary modifications.

## Installation

To install `fish-asdf`, you need to have `fisher` installed. If you don't have `fisher`, you can install it by running:

```fish
curl -sL https://git.io/fisher | source && fisher install jorgebucaran/fisher
```

Once `fisher` is installed, you can add the `fish-asdf` plugin by running:

```fish
fisher install seru/fish-asdf
```

## What does this plugin do?

The `fish-asdf` plugin sets up the required fish shell configuration for `asdf` to function properly. It ensures that:

- The `asdf` executable is available in your shell.
- The necessary environment variables are set up for `asdf` to manage versions of tools effectively.

This plugin is lightweight and does not include any additional features or modifications beyond what is required for `asdf` to work in the fish shell.