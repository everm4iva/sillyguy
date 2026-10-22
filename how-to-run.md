## How to run!
Here is a few dependencies needed to debug/run this correctly.

- [Node.js (+v22)](https://nodejs.org)
- Android SDK (just install android studio, it will be avaliable on your system)
- Java Development Kit (JDK +v17)

> Side note: you can use yarn/bun/deno or other runtimes besides nodejs 👀

How to actually run it:

```bash
# Install apache cordova (the actual framework)
npm install -g cordova

# Install project dependencies
npm install

# Install cordova dependencies
npm run dep

# Execute project (generates debug apk)
npm run start

# Build project (generates build/distribution-ready apk)
npm run build
```
> Note: If you are connected to your phone via USB/Network debbuging, the apk will install remotely on your phone without you having to move the `.apk` file cooked on build.

Some extra things:

```bash
# Clean command (to clean project + builds)
npm run clean

# WARNING: Deep clean command (cleans project + builds + lock files + node_modules)
npm run decl

# Useless test command
npm run test
```