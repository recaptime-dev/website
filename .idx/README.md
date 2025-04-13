# Contributing with Firebase Studio (previously Project IDX)

We officially configure a dev environment for Firebase Studio users (previously Project IDX),
based off [our `devenv.nix` config](../devenv.nix) with a few tweaks.

## How to open this repo?

Since `Open in Firebase Studio` deeplinks only support GitHub repos at the moment,
you have to use the GitHub mirror of this project first via the button below:

[![Open in Firebase Studio](https://cdn.firebasestudio.dev/btn/open_blue_32.svg)][deeplink]

<details>
<summary>Button not working?</summary>
If the button does not clickable on your side, you can copy the URL below and paste it in the address bar of a new browser window/tab and hit Enter.

```
https://studio.firebase.google.com/import?url=https%3A%2F%2Fgithub.com%2Frecaptime-dev%2Fwebsite
```

Alternatively, you can copy the GitHub mirror URL below and paste at [the project import screen](https://studio.firebase.google.com/import).

```
https://github.com/recaptime-dev/website
```
</details>

[deeplink]: https://studio.firebase.google.com/import?url=https%3A%2F%2Fgithub.com%2Frecaptime-dev%2Fwebsite

## Accessing the preview

Once your workspace is loaded up, a web preview tab should be loaded alongside
Gemini chat. Switch to that tab to load the web preview. If you accidentally closed it,
you can reopen it in different ways:

* **Via Firebase Studio view**: Shortcuts -> Preview Shortcuts -> select `Firebase Studio: Show Web Preview`
* **Directly on Command Pallete**: type **`Firebase Studio: Web Preview`** and select it
