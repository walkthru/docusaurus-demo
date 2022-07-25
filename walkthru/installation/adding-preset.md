---
title: Configuring preset
file: docusaurus.config.js
focus: 55-61
center: 58
---

You can add the WalkThru preset to Docusaurus via the config file.

To do this, add another array to the `preset` property. 

The first element of this array is the preset name i.e. `docusarus-preset-walkthru`. The second element of the array is the options object.

The only required option is `githubToken` (string). WalkThru requires a GitHub access token. It's recommended include this by using an *environment variable*.

Next, we'll see how to add environment variables to the Docusaurus config.
