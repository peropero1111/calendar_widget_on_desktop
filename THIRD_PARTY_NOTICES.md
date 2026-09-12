# THIRD-PARTY SOFTWARE AND TRADEMARK NOTICES

This document provides notices for third-party software and services used by
`calendar_widget_on_desktop`.

The MIT License in the root of this repository applies to the original source
code of `calendar_widget_on_desktop` for which the project author holds the
applicable copyright. Third-party software remains subject to its own license
terms and copyright notices.

---

## 1. Requests

**Package:** `requests`  
**License:** Apache License 2.0  
**License text:** [`LICENSES/Apache-2.0.txt`](LICENSES/Apache-2.0.txt)

`calendar_widget_on_desktop` uses Requests for HTTP communication.

Requests is licensed separately from this project. The project's MIT License
does not replace or modify the Apache License 2.0 terms applicable to Requests.

---

## 2. iCalendar

**Package:** `icalendar`  
**License:** BSD 2-Clause License  
**Copyright:** Copyright (c) 2012-2013, Plone Foundation  
**License text:** [`LICENSES/BSD-2-Clause.txt`](LICENSES/BSD-2-Clause.txt)

`calendar_widget_on_desktop` uses the `icalendar` package to parse iCalendar
data.

The `icalendar` package is licensed separately from this project.

---

## 3. recurring-ical-events

**Package:** `recurring-ical-events`  
**License:** GNU Lesser General Public License v3.0 or later
(`LGPL-3.0-or-later`)  
**License text:** [`LICENSES/LGPL-3.0.txt`](LICENSES/LGPL-3.0.txt)  
**GNU GPL v3 text:** [`LICENSES/GPL-3.0.txt`](LICENSES/GPL-3.0.txt)

`calendar_widget_on_desktop` uses `recurring-ical-events` to expand and process
recurring iCalendar events.

This library is licensed separately under the GNU Lesser General Public
License version 3 or later. The LGPLv3 incorporates the terms and conditions
of the GNU General Public License version 3 and supplements them with
additional permissions. For that reason, both license texts are included.

The MIT License of `calendar_widget_on_desktop` does not relicense
`recurring-ical-events`.

---

## 4. tzdata

**Package:** `tzdata`  
**License:** Apache License 2.0  
**License text:** [`LICENSES/Apache-2.0.txt`](LICENSES/Apache-2.0.txt)

The `tzdata` package may be used to provide time zone data required for date
and time processing.

It is licensed separately under the Apache License 2.0.

---

## 5. winotify

**Package:** `winotify`  
**License:** MIT License  
**Copyright:** Copyright (c) 2021 Versa Syahputra  
**License text:** [`LICENSES/MIT.txt`](LICENSES/MIT.txt)

`calendar_widget_on_desktop` uses `winotify` to display Windows notifications.

The copy of the MIT License in `LICENSES/MIT.txt` applies to `winotify` and
contains the copyright notice supplied by its upstream project. It is separate
from the root MIT License that applies to the original code of
`calendar_widget_on_desktop`.

---

## 6. x-wr-timezone

**Package:** `x-wr-timezone`  
**License:** GNU Lesser General Public License v3.0 or later
(`LGPL-3.0-or-later`)  
**License text:** [`LICENSES/LGPL-3.0.txt`](LICENSES/LGPL-3.0.txt)  
**GNU GPL v3 text:** [`LICENSES/GPL-3.0.txt`](LICENSES/GPL-3.0.txt)

`x-wr-timezone` may be installed as a dependency in the iCalendar processing
stack used by this project.

It is licensed separately under the GNU Lesser General Public License version
3 or later.

---

## 7. Bundled Executable Distributions

Compiled or packaged executable versions of `calendar_widget_on_desktop` may
contain additional third-party Python packages, runtime components, or other
dependencies that are not listed above.

Each bundled component remains subject to its own license, copyright notice,
attribution requirements, and redistribution conditions.

The exact dependency set may change according to package versions and the
build environment. Before distributing an executable build, the distributor
should inspect the packages actually included in that build and preserve all
license texts and notices required by those packages.

The files in `LICENSES/` are therefore not intended to imply that no other
third-party licenses may apply to a particular executable build.

---

## 8. Google Calendar and Google Trademarks

This project is an unofficial third-party project that can use iCalendar data
exported or provided by Google Calendar.

Google Calendar, Google, and related names and marks are trademarks of Google
LLC.

Their use in this project is solely for identification, compatibility, and
interoperability purposes.

`calendar_widget_on_desktop` is not affiliated with, sponsored by, approved
by, or endorsed by Google LLC.

No Google software is relicensed under the MIT License of this project.

---

## Project License

Except for separately licensed third-party software and third-party
intellectual property, the original source code of `calendar_widget_on_desktop`
is distributed under the MIT License.

See the root [`LICENSE`](LICENSE) file for the full project license terms.
