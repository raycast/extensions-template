# Template to store extensions for your private Store in Raycast

Automatically build & publish extensions to your private store in [Raycast](https://www.raycast.com/)

## :hammer_and_wrench: Features

- Easily build & publish your extensions to private store
- Collaborate on extensions through Pull Requests with automatic validation

## :robot: How to use ?

1. Click the [Use this template](https://github.com/raycast/extensions-template/generate) button and generate a repository from this template.
3. [Add a secret](https://docs.github.com/en/actions/security-guides/encrypted-secrets#creating-encrypted-secrets-for-a-repository) to generated repository named `RAYCAST_ORGANIZATION_TOKEN` with value being your [personal token](https://developers.raycast.com/teams-beta/publish-a-private-extension). You can read the `RAYCAST_ORGANIZATION_TOKEN` by running `ray token` on your local machine (or use the -C option to copy it to the clipboard automatically).
4. Checkout new repository and create your extension in `extensions` subfolder (example: `extensions/hello-world/package.json`).
5. Push your extension to the `main` branch and watch as the GitHub actions pick it up and publish it to your private store.

    Alternatively, push your extension to a different branch and create a Pull Requests for it that will validate it through automatic [status checks](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/collaborating-on-repositories-with-code-quality-features/about-status-checks). To publish it simply merge a Pull Request to the `main` branch.

## :page_with_curl: Documentation & Resources

- See [Raycast](https://www.raycast.com/) for downloading Raycast
- See [developers.raycast.com](https://developers.raycast.com/) for guides, examples, references, and more to help you build extensions.
- See [Getting Started](https://developers.raycast.com/teams-beta/getting-started) for Raycast for Teams
