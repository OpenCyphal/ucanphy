# UAVCAN/CAN Physical Layer Specification (UCANPHY)

[![CI](https://github.com/UAVCAN/ucanphy/actions/workflows/main.yml/badge.svg)](https://github.com/UAVCAN/ucanphy/actions)
[![Forum](https://img.shields.io/discourse/https/forum.uavcan.org/users.svg)](https://forum.uavcan.org)

The UAVCAN/CAN Physical Layer specification is maintained here.
This work is coordinated on the UAVCAN Forum at <https://forum.uavcan.org/c/consortium/ucanphy/21>.

## Editing guide

The editing guide of the [UAVCAN Specification](https://github.com/UAVCAN/specification) shall be adhered to.

## Tools

See the instructions for the [UAVCAN Specification](https://github.com/UAVCAN/specification) for further info.

### Compiling

A GNU/Linux-based operating system is assumed.
In order to compile the document, install TeX Live
(Ubuntu packages: [`texlive-full`](https://packages.ubuntu.com/xenial/texlive-full)).
When done, run `./compile.sh`.

### IDE setup

First, ensure that you can compile the document as described above.
Do not proceed further until that requirement is satisfied.

Use Visual Studio Code with extensions `James-Yu.latex-workshop` and `ban.spellright` for editing.
More info in the [Zubax Knowledge Base](https://kb.zubax.com/x/IYEh).

If you're using Visual Studio Code there are local settings for `latex-workshop` and you can use
the `.vscode/spellright.dict` to squelch bogus spelling errors from Spellright.
