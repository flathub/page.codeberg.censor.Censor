<!--
SPDX-FileCopyrightText: 2025 Robert Wolff <mahlzahn@posteo.de>
SPDX-License-Identifier: CC0-1.0
-->

# Censor – PDF Document Redaction for the GNOME Desktop

Censor is a PDF document redaction tool. It permanently removes text and images
in redacted areas and can draw rectangles over them. It uses the [MuPDF][]
library with its python bindings from the [PyMuPDF][] module.

[MuPDF]: https://mupdf.com
[PyMuPDF]: https://mupdf.com/pymupdf

## Installing

Get [Censor on Flathub][].

[Censor on Flathub]: https://flathub.org/apps/page.codeberg.censor.Censor

## Contributing

Use [GNOME Builder][] to develop and build Censor. Localize Censor using
[Codeberg Translate][]. See the [Censor Contributing Guide][Contribute] for
information on translation, testing, commit messages, releases, etc.

[GNOME Builder]: https://apps.gnome.org/Builder
[Contribute]: https://codeberg.org/censor/Censor/src/branch/main/CONTRIBUTING.md
[Codeberg Translate]: https://translate.codeberg.org/engage/censor

## Donating

Support Censor indirectly by [donating to Codeberg][Codeberg Donate]. Thanks to
[Codeberg][] for providing the git hosting platform with continuous integration
and all the nice features of [Forgejo][] and [Weblate][] needed for the
development of Censor. Further, I want to express my gratitude to [GNOME][] and
[Flathub][] for providing resources needed for building and distributing test
and release packages.

[Codeberg Donate]: https://donate.codeberg.org
[Codeberg]: https://codeberg.org/about
[Forgejo]: https://forgejo.org
[Weblate]: https://weblate.org
[GNOME]: https://www.gnome.org/
[Flathub]: https://flathub.org/

## Copying

Copyright 2025 Robert Wolff <mahlzahn@posteo.de>

Censor’s source code is licensed under the [GNU General Public License][GPL-3.0]
as published by the Free Software Foundation, either version 3 of the License,
or (at your option) any later version (`GPL-3.0-or-later`). Its artwork is
licensed under the
[Creative Commons Attribution-ShareAlike 4.0 International][CC-BY-SA-4.0]
license (`CC-BY-SA-4.0`).

Any distributed build or package of Censor, which necessarily includes the
AGPL-licensed libraries PyMuPDF and MuPDF, is subject to the
[GNU Affero General Public License][AGPL-3.0], version 3 only (`AGPL-3.0-only`).

[AGPL-3.0]: https://www.gnu.org/licenses/agpl-3.0.html
[GPL-3.0]: https://www.gnu.org/licenses/gpl-3.0.html
[CC-BY-SA-4.0]: https://creativecommons.org/licenses/by-sa/4.0
