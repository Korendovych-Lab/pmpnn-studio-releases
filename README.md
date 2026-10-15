# PMPNN Studio — releases

Installers for **PMPNN Studio**, a desktop interface for
[ProteinMPNN](https://github.com/dauparas/ProteinMPNN), built for binder discovery in the
Korendovych lab.

This repository holds only the release artifacts. It is public so that downloads and
in-app updates work without a GitHub account; the source lives in a separate private
repository.

## Download

Get the latest installer from [Releases](../../releases/latest).

| System | File |
|---|---|
| Windows 10/11 | `PMPNN Studio_<version>_x64-setup.exe` |
| macOS 11+, Apple silicon | `PMPNN Studio_<version>_aarch64.dmg` |
| Linux | `.AppImage`, or `.deb` for Debian and Ubuntu |

Everything needed to run designs is included — Python, PyTorch and the model weights.
There is no conda environment to set up, nothing is downloaded on first launch, and
designs run entirely on your own machine.

The Windows installer is unsigned, so SmartScreen shows a warning: choose **More info**,
then **Run anyway**. It installs per-user and needs no administrator rights.

## Credit

Sequence design is performed entirely by ProteinMPNN. If you use designs from this app,
cite:

> Dauparas J, Anishchenko I, Bennett N, et al. Robust deep learning-based protein sequence
> design using ProteinMPNN. *Science* 378, 49–56 (2022).

ProteinMPNN is released under the MIT License, Copyright (c) 2022 Justas Dauparas. This
app is not affiliated with its authors.
