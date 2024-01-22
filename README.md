<!--
SPDX-FileCopyrightText: Copyright 2023 Andreas Sandberg <andreas@sandberg.uk>

SPDX-License-Identifier: Apache-2.0
-->

# What is RF Chameleon

RF Chameleon is a set of tools to interface with ISM-band radios. It's
inspired by [RFQuack](https://rfquack.org/) but provides a more
abstract interface to the radio which implies that it needs to make
more assumptions about the underlying protocol. Unlike RFQuack, RF
Chameleon is not intended as an RF exploration tool. RF Chameleon is
intended to be used in the phase after basic exploration when the
underlying radio parameters are known.

This repository contains custom boards that have been designed
specifically for RF Chameleon.

# Firmware

See the
[rfchameleon-fw](https://github.com/rfchameleon/rfchameleon-fw)
project for more details.

# Boards

## RF Chameleon CC1101

This board is based on an STM32F401 and a [eByte
E07](https://www.cdebyte.com/products/E07-900MM10S) module containing
a [Texas Instruments CC1101](https://www.ti.com/product/CC1101) radio.

Early revisions of this board was known as the *RF McQuack CC1101*.

**Warning:** Revision 1 of this board has several known hardware
   defects that require patching before the board can be used.
