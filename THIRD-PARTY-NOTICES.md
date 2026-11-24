# Third-Party Notices — ONetX

This tool is distributed as a single pre-built executable. It bundles the
third-party components listed below. Each component remains the property of
its respective copyright holders and is used under its own license, whose
full text is reproduced in this file.

**Owlsec LLC's own source code is proprietary and is not covered by any of
the licenses below.** Those licenses apply only to the third-party components
named here.

- Tool binary: `ONetX`
- SHA-256: `b9fd3d54259de85dfd46b349acc83fddc5941acc9ac1f149d2e26a77bca3126e`
- Bundled interpreter: CPython 3.11 (PSF License)
- Generated: 2026-11-24
- Machine-readable inventory: see `SBOM.cdx.json` in this repository

## Components

| Component | Version | License |
|---|---|---|
| pyyaml | 6.0.3 | MIT |
| tqdm | 4.70.1 | MPL-2.0 AND MIT |
| CPython | 3.11 | PSF-2.0 |
| Python standard library | 3.11 | PSF-2.0 |

Shared system libraries from Debian (for example `libssl`, `libz`, `libbz2`) are bundled unmodified by PyInstaller and are governed by their own licenses as shipped by the Debian project. The exact versions are listed in `SBOM.cdx.json`.

---

## Full license texts

### pyyaml 6.0.3

- Author: Kirill Simonov
- Project: https://pyyaml.org/
- Declared license: MIT

<details>
<summary><code>LICENSE</code></summary>

```text
Copyright (c) 2017-2021 Ingy döt Net
Copyright (c) 2006-2016 Kirill Simonov

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

</details>

### tqdm 4.70.1

- Project: https://tqdm.github.io
- Declared license: MPL-2.0 AND MIT

<details>
<summary><code>LICENCE</code></summary>

```text
`tqdm` is a product of collaborative work.
Unless otherwise stated, all authors (see commit logs) retain copyright
for their respective work, and release the work under the MIT licence
(text below).

Exceptions or notable authors are listed below
in reverse chronological order:

* files: *
  MPL-2.0 2015-2026 (c) Casper da Costa-Luis
  [casperdcl](https://github.com/casperdcl).
* files: tqdm/_tqdm.py
  MIT 2016 (c) [PR #96] on behalf of Google Inc.
* files: tqdm/_tqdm.py README.rst .gitignore
  MIT 2013 (c) Noam Yorav-Raphael, original author.

[PR #96]: https://github.com/tqdm/tqdm/pull/96


Mozilla Public Licence (MPL) v. 2.0 - Exhibit A
-----------------------------------------------

This Source Code Form is subject to the terms of the
Mozilla Public License, v. 2.0.
If a copy of the MPL was not distributed with this project,
You can obtain one at https://mozilla.org/MPL/2.0/.


MIT License (MIT)
-----------------

Copyright (c) 2013 noamraph

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```

</details>

---

## Python Software Foundation License

The bundled CPython interpreter and standard library are distributed under the PSF License Agreement: <https://docs.python.org/3/license.html>
