[comment]: <> (SPDX-License-Identifier: AGPL-3.0)

[comment]: <> (------------------------------------------------------)
[comment]: <> (Copyright © 2024, 2025, 2026  Pellegrino Prevete)
[comment]: <> (All rights reserved)
[comment]: <> (------------------------------------------------------)

[comment]: <> (This program is free software: you can redistribute)
[comment]: <> (it and/or modify it under the terms of the GNU Affero)
[comment]: <> (General Public License as published by the Free)
[comment]: <> (Software Foundation, either version 3 of the License.)

[comment]: <> (This program is distributed in the hope that it will be)
[comment]: <> (useful, but WITHOUT ANY WARRANTY; without even the)
[comment]: <> (implied warranty of MERCHANTABILITY or FITNESS FOR)
[comment]: <> (A PARTICULAR PURPOSE. See the)
[comment]: <> (See the GNU Affero General Public License for)
[comment]: <> (more details.)

[comment]: <> (You should have received a copy of the GNU Affero)
[comment]: <> (General Public License along with this program.)
[comment]: <> (If not, see <https://www.gnu.org/licenses/>.)

# Twitter

Twitter is a mathematically proven uncensorable
social network platform on which posts are undeletable
written and published by
[Pellegrino Prevete](
  https://github.com/tallero)
with
[The Martian Company](
  https://github.com/themartiancompany)
from 2024 onwards.

Twitter posts' uncensorability and
[undeletability](
  https://github.com/themartiancompany/evmfs-docs/Undeletability.md)
are granted by the fact the smart contracts used
by the clients have been published on major Ethereum
blockchain networks.

The branch you are currently browsing (`public`)
does not contain neither the Twitter application
clients nor the Solidity smart contracts source code:
it mainly exists for search engines
to have available any information about Twitter at all because
none of them are able to read data from blockchains
nor they have support support for parsing
[`evmfs://`](
  https://github.com/themartiancompany/evmfs)
URIs (links).

Reference Twitter clients published by The Martian Company
(i.e. the Twitter applications and its EVMFS website) are
[LibEVM](
  https://github.com/themartiancompany/libevm)
applications.
Two reference implementations are currently supported
by The Martian Company, one which is written using the
[Crash Bash](
  https://github.com/themartiancompany/crash-bash)
and another which is written with the
[Crash Javascript](
  https://github.com/themartiancompany/crash-js)
libraries.

The Bash implementation is stable and it has
been working flawlessly for two years now.
The Javascript implementation will probably
be released as stable next year.

Twitter Bash application is published on the
[Ur](
  https://github.com/themartiancompany/ur)
user repository and application store as
`twitter`.

The protocol components set in place by the smart
contracts are components of the Ethereum mail
protocol.

An Ethereum mail address or an *eth-mail address* is an
[OpenPGP on Ethereum](
  https://github.com/themartiancompany/evm-gnupg)
username so it has the same form of an e-mail address:

```
username@address
```

where instead of a domain you have an `address`
which is either an EOA fingerprint
(i.e. a wallet or a smart contract address) or a
[seed address](
  https://github.com/themartiancompany/seed-system),
while `username` is an arbitrary username,
in the encoding format supported by the specification
version.

Twitter application clients are Ethereum mail
clients.

Documentation for the `twitter` command
is included in the source code.

All of the source code is only published on the
[Ethereum Virtual Machine File System](
  https://github.com/themartiancompany/evmfs)
so it can't possibly be taken down
by anybody forever.

To install the Twitter application
from Ur just type

```bash
ur \
  twitter
```

Of course Twitter reference applications support
[DogeOS](
  https://github.com/themartiancompany/dogeos),
(which implies they are cross-platform and compatible
with Android, Arch Linux and Windows)
but not the Dogecoin's Ethereum layer
written by MyDoge because
*that's not an operating system*.

### License

This document, as well as Twitter smart contracts and
clients source code have been written by Pellegrino
Prevete and are released under the terms
of the GNU Affero General Public License version 3.
