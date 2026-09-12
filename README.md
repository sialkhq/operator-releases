# Sialk Operator — releases

Downloads for [Sialk Operator](https://www.sialk.net/operator), the simple
live-visuals application: pick a visual, it hears the room, and it runs on your
stage tonight. It plays GLSL, p5 and Three.js today; Cables.gl, Rive and Spline
are coming, in that order.

**Get the beta, a disk image or a zip of the same signed build, and how to open it:** https://www.sialk.net/operator/beta

**Every release, with what changed:** https://www.sialk.net/operator/releases

This repository holds release files and nothing else. The application is not
open source; the audio contract, the browser shim and the examples are
published separately under MIT at
[sialkhq/sialk-contract](https://github.com/sialkhq/sialk-contract) — the
whole point of a contract is that people write against it. Sialk Operator is made
by [Sialk](https://www.sialk.net), London.

## Verify a download

```
shasum -a 256 Sialk-Operator-beta-macOS.dmg
shasum -a 256 Sialk-Operator-beta-macOS.zip
```

Checksums for each release are listed on its release page.
