this repo reproduces several issues in bit@14.6.0 and overries+propagate

first issue - after cloning this repo and runing `bit init` i get an error on `bit status` saying:

```
unable to manually add the dependency "react" into "button".
it's not an existing component, nor existing package
```

second issue - (need to try and reproduce the issue) by adding `moment` to `utils/datetime` `button`
gets `moment` as a dependency as well.

