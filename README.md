# captdriver

📣 **IMPORTANT NOTE to Fellow Hackers who Have Forked This Repo** 📣

A rebase has been scheduled for this repository. Changes that you have
made may not easily merge after the rebase. However, I will try my best
to preserve the current state of the repository (maybe in an alternate
branch?).

A definitve timeline for the rebase will be given at a later date.

This is to incorporate changes from unexpected pull requests that got
[merged into Alexey's original repo](https://github.com/agalakhov/captdriver/commits/master),
specifically #39 to #45. These PRs add most features that were previously
only available on this fork, along with updates to SPECS and the build
files. However, this fork has diverged enough to make a trivial merge 
impossible.

The upcoming rebase aims to restore similarity with the original codebase
and the ability to transfer enhancements and bugfixes between the two repos.

## Foreword
**Captdriver is a free (as in speech) alternative driver** for Canon 
printers that can only accept the proprietary CAPT data stream format.
It aims to be a reliable and truly portable alternative driver. 
It's free and open source, so you can take part in its development, 
and help with expanding support, adding new features, and most importantly,
maintaining its codebase.

As Captdriver is almost completely written in C, and uses the 
Common Unix Printing System (*CUPS*), it is potentially compatible
with any operating system with a working copy of CUPS, regardless of
hardware architecture.

As a bonus for users on x86-64 hardware, Captdriver eliminates the
need to install 32-bit libraries on your 64-bit operating system.

## Status
Captdriver is currently admittedly far from complete. The driver is
under active development, but updates are sporadic. For details, look
in these places:

* [Releases](https://github.com/mounaiban/captdriver/releases)
* [Issues](https://github.com/mounaiban/captdriver/issues)
* [Issues on the original repository](https://github.com/agalakhov/captdriver/issues)
* [Wiki](https://github.com/mounaiban/captdriver/wiki)

Four printer families have been successfully used with this driver:

* LBP2900/LBP2900B
* LBP3000
* LBP3010/LBP3018/LBP3050
* [LBP3100/LBP3108/LBP3150](https://github.com/agalakhov/captdriver/issues/13)

## Acknowledgements
This driver is based on the works of Rildo Pragana, Nicolas Boichat,
Alexey Galakhov, Benoit Bolsee and Vitaliy Tomin. Special thanks to
the other [contributors](https://github.com/agalakhov/captdriver/graphs/contributors)
who made this driver possible, and the folks who donated their spare
time to test and review my edits!

## Installation and Setup
This software must be manually installed. Please refer to Mounaiban's
[Captdriver Wiki for detailed instructions](https://github.com/mounaiban/captdriver/wiki/Building-and-Installing-captdriver:-A-Unified-Guide).

## Technical Information
Details of the CAPT format are documented in the `SPECS` file.
While incomplete and expected to contain errors and omissions, 
help with expanding it and making corrections is greatly 
appreciated. Please also check the [wiki] for detailed information 
not yet added to this file.

## Disclaimers
Please use this driver at your own risk. As with any software licensed
under the *GNU General Public License 3.0*, there is NO WARRANTY.
Full terms and conditions are detailed in the file named `COPYING`.

This is unofficial software not endorsed by Canon Inc. or any of its
affiliates.

macOS is a registered trademark of Apple Inc, registered in the U.S. and other countries and regions.

Windows is a trademark of Microsoft Corporation.

[ibm]: https://www-01.ibm.com/support/docview.wss?uid=nas8N1019527 "IBM. IBM Information on Printers by Canon. IBM Support. 
Reference #N1019527. Updated 2017-03-28."

[wiki]: https://github.com/mounaiban/captdriver/wiki "Mounaiban's captdriver Wiki."
