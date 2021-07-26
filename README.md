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


Using the Stylelint config
--------------------------

Add a `.stylelintrc.yml` to your project, containing:

```yaml
extends:
    - './node_modules/@21torr/ci-npm/stylelint/.stylelintrc.yml'
```
