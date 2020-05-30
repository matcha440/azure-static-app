# About this template

Use this template to create a starting point for a site generated by Hugo.  If running within VS Code or an online Codespace, a devcontainer will be setup automatically with Hugo and other useful extensions pre-installed.

## Upgrading the version of Hugo

The version of Hugo used in the devcontainer is set by a build arg that can be found in `devcontainer.json`.

```JavaScript
"build": {
  "args": {
    "HUGO_VERSION": "0.71.1"
  }
}
```

Be sure to rebuild your container after changing this value.
