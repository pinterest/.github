# Open Source Project Template

This repository serves as a template for Pinterest's open source projects. It
contains the canonical copies of common files for licensing, contribution,
etc.

- [`LICENSE`](LICENSE) - our standard [Apache 2.0 license](https://www.apache.org/licenses/LICENSE-2.0)

## Licensing

In addition to including the [`LICENSE`](LICENSE) file in the root of your
repository, you should also add the following comment header to *all* of your
project's source files (using the current year in place of `[yyyy]`):

    Copyright [yyyy]-present, Pinterest, Inc.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

For the purposes of licensing, all significant project files are considered
"source files". However, it doesn't make sense to add license headers to files
such as:

 - Short information text files (`README`, etc.)
 - Test data that would become malformed with the addition of the license text

Large projects may also use a shorter per-file copyright header, such as:

    /**
     * Copyright (c) [yyyy]-present, Pinterest, Inc.
     *
     * This source code is licensed under the Apache License, Version 2.0
     * found in the LICENSE file in the root directory of this source tree.
     */

Lastly, please ensure that the `LICENSE` file is included as part of all
release packages and distribution archives, including things like JAR files.
