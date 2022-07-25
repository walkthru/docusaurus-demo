---
title: Dotenv
file: docusaurus.config.js
focus: 6
center: 6
---

To include your environment variables in the Docusaurus config you can use the `dotenv` package.

This package is already a dependency of Docusaurus so you won't need to install it.

You will, however, need to require it at the top of your Docusaurus config file.

Now your environment variables will be available as properties of the `process.env` object e.g. `process.env.GH_PAT`.
