# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

This is a error reproduction repo for the issue here: [[Yarn] Error When Installing Package: "command not found: patch-package"](https://github.com/Expensify/react-native-live-markdown/issues/573)

## Get started

1. Install dependencies

   ```bash
   yarn install
   ```

See error:

```
➤ YN0000: ┌ Link step
➤ YN0007: │ @expensify/react-native-live-markdown@npm:0.1.199 [4ebec] must be built because it never has been before or the last one failed
➤ YN0009: │ @expensify/react-native-live-markdown@npm:0.1.199 [4ebec] couldn't be built successfully (exit code 127, logs can be found here: /private/var/folders/04/d5gndjrd4bg3wcd6d1n_h8vr0000gn/T/xfs-118fb175/build.log)
➤ YN0000: └ Completed in 7s 509ms
➤ YN0000: Failed with errors in 9s 310ms
```

`build.log`:
```
# This file contains the result of Yarn building a package (@expensify/react-native-live-markdown@virtual:4ebec940cecc17a5e71591f2b19524da5e082df6a9a486d4520b54da6110f56072da8631415ea3095bc355968e67f9cfa6cb67145fc3af5616c0408b04a40b79#npm:0.1.199)
# Script name: postinstall

command not found: patch-package
```
