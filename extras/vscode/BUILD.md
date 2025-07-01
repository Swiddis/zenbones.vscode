## Build zenbones themes

`make`

## Update version

Edit `package.json`.

## Generate package.json

`./generate.sh`

## Debug extension

Press F5 in VS Code.

## Package extension

Install the `vsce` and `ovsx` CLIs, then:

`vsce package`

## Publish extension

```
# VSCode Marketplace
$ vsce publish

# Open VSX Registry
$ ovsx publish
```
