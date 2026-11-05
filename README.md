# UI Themes

Community-created UI themes for the HDOS client. Use the branch menu above to browse them.

## Credits

Each theme should include a README naming its creator and crediting any other assets used, if applicable.

See the [Theme License](LICENSE.md) for usage and attribution details.

## Contributing

### Add a theme

1. Fork this repository and leave **Copy the master branch only** unchecked so your fork includes `theme-template`.
2. In your fork, create a branch from `theme-template`. Choose an unused name starting with `theme-`, such as `theme-osrs-modern`.
3. Add your theme files and update the README with the theme's name, description and credits, then commit and push the branch to your fork.
4. Open a pull request to `hdos-dev/ui-themes`, setting **base** to `theme-template` and **compare** to your theme branch.

### Update a theme

1. Fork this repository if you haven't already, leaving **Copy the master branch only** unchecked.
2. In your fork, select the theme branch you want to update, such as `theme-modern-2010`. Use **Sync fork → Update branch** to get the latest changes. If you work in IntelliJ or VS Code, pull that branch before editing.
3. Edit the theme files directly on that branch in your fork, then commit and push your changes.
4. Open a pull request to `hdos-dev/ui-themes`. Set **base** to its existing theme branch (`theme-modern-2010` in this example) and **compare** to the same-named branch in your fork.

Updates are checked and reviewed before merging.
