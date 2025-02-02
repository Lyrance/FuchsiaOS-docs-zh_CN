# Install Fuchsia on a device

The Fuchsia platform can be installed on the following hardware devices:

- [Chromebooks][install-fuchsia-on-chromebook]
- [Intel NUC (Next Unit of Computing) devices][install-fuchsia-on-nuc]
- [Khadas VIM3 board][install-fuchsia-on-vim3]

## Architecture support

Fuchsia supports two ISAs (Instruction Set Architectures):

* `arm64` - Fuchsia supports `arm64` (also called AArch64) with no restrictions on
  supported microarchitectures.

* `x86-64` - Fuchsia supports `x86-64` (also called IA32e or AMD64), but with some
  restrictions on supported microarchitectures.

## CPU support

Fuchsia's support for CPUs:

* Intel - For Intel CPUs, only Broadwell and later are actively supported and will
  have new features added for them.  Additionally, we will accept patches to keep
  Nehalem and later booting.

* AMD - AMD CPUs are **not** actively supported (in particular, we have no active testing
  on them), but we will accept patches to ensure correct booting on them.

## Table of contents

- [Install Fuchsia on a Chromebook][install-fuchsia-on-chromebook]
- [Install Fuchsia on a NUC][install-fuchsia-on-nuc]
- [Install Fuchsia on a NUC using Zedboot (Legacy)][install-fuchsia-on-nuc-legacy]
- [Install Fuchsia on a Khadas VIM3 board][install-fuchsia-on-vim3]
- Create a bootable Fuchsia image:
  - [Install Fuchsia from a USB flash drive][prepare-usb]
  - [Use the Fuchsia installer (Legacy)][use-the-installer-legacy]
- Set up experimental hardware:
  - [Install Fuchsia on Acer Switch Alpha 12][install-fuchsia-on-acer12]
  - [Install Fuchsia on Toulouse][install-fuchsia-on-toulouse]

<!-- Reference links -->

[install-fuchsia-on-chromebook]: /development/hardware/chromebook.md
[install-fuchsia-on-nuc]: /development/hardware/intel_nuc.md
[install-fuchsia-on-nuc-legacy]: /development/hardware/intel_nuc_with_zedboot.md
[install-fuchsia-on-vim3]: /development/hardware/khadas-vim3.md
[prepare-usb]: /development/hardware/usb_setup.md
[use-the-installer-legacy]: /development/hardware/installer.md
[install-fuchsia-on-acer12]: /development/hardware/acer12.md
[install-fuchsia-on-toulouse]: /development/hardware/toulouse.md
