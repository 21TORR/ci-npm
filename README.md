CI Config: NPM
===============

Our shared config for all CI tools that are installed via (p)npm.


Using the ESLint config
-----------------------

Add a `.eslintrc.yaml` to your project, containing:

```yaml
extends:
    - './node_modules/@21torr/ci-npm/eslint/{package}.yaml'
```

### Next.js

In a Next.js project, you should use:

```yaml
extends:
    - './node_modules/@21torr/ci-npm/eslint/next.js-jsonly.yaml'
    - './node_modules/@21torr/ci-npm/eslint/includes/typescript.yaml'
    - "next"
    - "next/core-web-vitals"
```


Using the Stylelint config
--------------------------

Add a `.stylelintrc.yml` to your project, containing:

```yaml
extends:
    - './node_modules/@21torr/ci-npm/stylelint/.stylelintrc.yml'
```
