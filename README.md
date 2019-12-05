Adding `propagate` causes Bit to say other components that should not be affected are modified.

STR:

1. `git clone`
1. `npm i`
1. `bit init`
1. `bit tag -a`
1. Add `"propagate": true` to the specific components `others/tab-navigation` and `utils/datetime`.
1. Run `bit status`
1. see that `button` is modified

