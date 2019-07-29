# Persistant `nix-shell`
nix-shell script to make derivations persistant, and avoid Nix garbage collection

## Usage

`p-shell` followed by the path to the Nix shell definition. This will create a gc-root in the parent directory of the Nix shell.

**Example:**
`p-shell ~/shells/node-build.nix`

## Acknowledgments

https://github.com/NixOS/nix/issues/979
