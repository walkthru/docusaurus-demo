---
title: .env file
file: docusaurus.config.js
focus: 6
center: 6
---

To create an env file you'll first need to copy the *.env.example* file:

```
cp .env.example .env
```

Make sure you put your GitHub access token here.

```
GH_PAT=
```

In the Docusaurus config file, require `dotenv` (it should already be installed) and your environment variables will be 
available e.g. `process.env.GH_PAT`.
