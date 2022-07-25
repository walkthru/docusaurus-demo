---
title: .env file
file: .gitignore
focus: 22
center: 22
---

To include environment variables in your project you'll need to add a *.env* file to your project.

```
touch .env
```

Add a variable to this `GH_PAT` and assign to it your GitHub access token.

```
GH_PAT=
```

Be sure to exclude this file from your version control by adding it to `.gitignore`.
