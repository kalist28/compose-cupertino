[![Maven Central](https://img.shields.io/maven-central/v/io.github.kalist28/cupertino)](https://maven-badges.herokuapp.com/maven-central/io.github.kalist28/cupertino)

[![Main Workflow](https://github.com/kalist28/compose-cupertino/actions/workflows/buildAndPush.yml/badge.svg)](https://github.com/kalist28/compose-cupertino/actions/workflows/buildAndPush.yml)

# compose-cupertino

This is a fork of [schott12521/compose-cupertino](https://github.com/schott12521/compose-cupertino) a fork of [alexzhirkevich/compose-cupertino](https://github.com/alexzhirkevich/compose-cupertino) except its been updated to work with CMP 1.7+

Additionally this repo has automated builds to enable faster releases, to take advantage of new compose multiplatform features as they become available.

# Usage

This package is published to Maven Central Repository: [cupertino-core on Maven Central](https://central.sonatype.com/artifact/io.github.kalist28/cupertino-core)

Depend on the [latest version](https://github.com/kalist28/compose-cupertino/releases) by declaring this in libs.versions.toml:

```
cupertino = "$latestVersion"

cupertino = { group = "io.github.kalist28", name = "cupertino", version.ref = "cupertino" }
cupertino-adaptive = { group = "io.github.kalist28", name = "cupertino-adaptive", version.ref = "cupertino" }
cupertino-decompose = { group = "io.github.kalist28", name = "cupertino-decompose", version.ref = "cupertino" }
cupertino-native = { group = "io.github.kalist28", name = "cupertino-native", version.ref = "cupertino" }
cupertino-icons-extended = { group = "io.github.kalist28", name = "cupertino-icons-extended", version.ref = "cupertino" }
```

## Try it

Wanna see what the library feels like? The latest version builds and deploys the Kotlin/WasmJS target to github pages: https://kalist28.github.io/compose-cupertino/

# License

Note: As of release 2.0.8, this forked library has been updated copyright headers to fully comply with the Apache 2.0 license copied from the original: https://github.com/alexzhirkevich/compose-cupertino/blob/master/LICENSE.txt

# Contributions

Contributions are always appreciated! Since builds to maven central go through GitHub Actions, we can get your changes in quickly. 

Ensure that the copyright information is included in your file(s):

```
/*
 * Copyright (c) 2023-2024. Compose Cupertino project and open source contributors.
 * Copyright (c) 2025. Scott Lanoue.
 *
 * Licensed under the Apache License, Version 2.0 (the "License");
 * you may not use this file except in compliance with the License.
 * You may obtain a copy of the License at
 *
 *     http://www.apache.org/licenses/LICENSE-2.0
 *
 * Unless required by applicable law or agreed to in writing, software
 * distributed under the License is distributed on an "AS IS" BASIS,
 * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 * See the License for the specific language governing permissions and
 * limitations under the License.
 */
```

Ideally you set up Android Studio / IDE to handle copyright notices for you: https://stackoverflow.com/a/48718711/1730421

# Disclaimer

Note this repo is not officially supported in any capacity; changes will be applied upstream when applicable ([example1](https://github.com/alexzhirkevich/compose-cupertino/pull/74), [example2](https://github.com/alexzhirkevich/compose-cupertino/pull/77))

# *P.S

Thanks to [schott12521](https://github.com/schott12521) for fix original fork and automated builds.