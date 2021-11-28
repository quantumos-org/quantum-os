<p align=center>
  <img src="assets/Quantum.png" width="300" height="300"/>
  <a href="https://www.quantum-os.org"><h1 align=center>Quantum OS - Be quantized!</h1></a>
</p>

<p align=center>
  <a href="https://reactos.org/project-news/reactos-0413-released/">
    <img alt="ReactOS 0.4.13 Release" src="https://img.shields.io/badge/release-0.4.13-0688CB.svg">
  </a>
  <a href="https://reactos.org/download/">
    <img alt="Download ReactOS" src="https://img.shields.io/badge/download-latest-0688CB.svg">
  </a>
  <a href="https://sourceforge.net/projects/reactos/">
    <img alt="SourceForge Download" src="https://img.shields.io/sourceforge/dm/reactos.svg?colorB=0688CB">
  </a>
  <a href="https://github.com/reactos/reactos/blob/master/COPYING">
    <img alt="License" src="https://img.shields.io/badge/license-GNU_GPL_2.0-0688CB.svg">
  </a>
  <a href="https://reactos.org/donate/">
    <img alt="Donate" src="https://img.shields.io/badge/%24-donate-E44E4A.svg">
  </a>
  <a href="https://twitter.com/reactos">
    <img alt="Follow on Twitter" src="https://img.shields.io/twitter/follow/reactos.svg?style=social&label=Follow%20%40reactos">
  </a>
</p>
<br />

Build Type                    | Status                                                                                                                                                                           | Artifacts
----------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------
**Intel x86-64**                 | [![Status](https://storage.googleapis.com/tensorflow-kokoro-build-badges/ubuntu-cc.svg)](https://storage.googleapis.com/tensorflow-kokoro-build-badges/ubuntu-cc.html)           | [PyPI](https://pypi.org/project/tf-nightly/)
**AMD x86-64**                 | [![Status](https://storage.googleapis.com/tensorflow-kokoro-build-badges/ubuntu-gpu-py3.svg)](https://storage.googleapis.com/tensorflow-kokoro-build-badges/ubuntu-gpu-py3.html) | [PyPI](https://pypi.org/project/tf-nightly-gpu/)
**Atmel x86-64**                     | [![Status](https://storage.googleapis.com/tensorflow-kokoro-build-badges/macos-py2-cc.svg)](https://storage.googleapis.com/tensorflow-kokoro-build-badges/macos-py2-cc.html)     | [PyPI](https://pypi.org/project/tf-nightly/)
**Cyrix x64**               | [![Status](https://storage.googleapis.com/tensorflow-kokoro-build-badges/windows-cpu.svg)](https://storage.googleapis.com/tensorflow-kokoro-build-badges/windows-cpu.html)       | [PyPI](https://pypi.org/project/tf-nightly/)
**ARM x86-64**               | [![Status](https://storage.googleapis.com/tensorflow-kokoro-build-badges/windows-gpu.svg)](https://storage.googleapis.com/tensorflow-kokoro-build-badges/windows-gpu.html)       | [PyPI](https://pypi.org/project/tf-nightly-gpu/)
**UMC x86-64**                   | [![Status](https://storage.googleapis.com/tensorflow-kokoro-build-badges/android.svg)](https://storage.googleapis.com/tensorflow-kokoro-build-badges/android.html)               | [Download](https://bintray.com/google/tensorflow/tensorflow/_latestVersion)
**IBM**      | [![Status](https://storage.googleapis.com/tensorflow-kokoro-build-badges/rpi01-py3.svg)](https://storage.googleapis.com/tensorflow-kokoro-build-badges/rpi01-py3.html)           | [Py3](https://storage.googleapis.com/tensorflow-nightly/tensorflow-1.10.0-cp34-none-linux_armv6l.whl)
**MIPS**      | [![Status](https://storage.googleapis.com/tensorflow-kokoro-build-badges/rpi23-py3.svg)](https://storage.googleapis.com/tensorflow-kokoro-build-badges/rpi23-py3.html)           | [Py3](https://storage.googleapis.com/tensorflow-nightly/tensorflow-1.10.0-cp34-none-linux_armv7l.whl)
  
<br />

# 🤔 What is Quantum Computing?
The main thing that differs normal computers from quantum computers are the QuBits. QBits are like normal Bits, a normal bit can only be <b>0</b> or <b>1</b>.
But a QuBits on the other hand can be <b>0</b> AND <b>1</b>. That means a normal byte with 8 bits on a normal computer can contains the same information on a quantum computer but it only needs 4 QuBits for the same information.

<img src="assets/Example-2.png" width="400" height="400"/>

# 💰 Bitcoin & Lightcoin & Etherium Miner
A good reason for Quantum OS is the BLE Miner (Bitcoin, Lightcoin, Etherium Miner). With this external feature you can mine cryptocoins.
Go to: https://quantom-os.org/ble-miner to get more informations about it. 

<img src="assets/Mine.png" />

# ☕ Download & Install
If you wan't to download QuantumOS you need the following tools:

Tools:
* <a href="https://git-scm.com/downloads">Git</a>
* <a href="https://pypip.org">PIP</a>
* <a href="https://nasm.org">Nasm</a>
* <a href="https://github.com/gcc-mirror/gcc.git">Gnu Cross Compiler</a>
* <a href="https://cmake.org/download/">CMake</a>
* <a href="https://www.gnu.org/software/make/">Makefile</a>
* <a href="https://www.python.org/downloads/">Python 3.x</a>

Then execute:

```git clone https://github.com/LeotendoDev/quantum-os.git```

```cd quantum-os/```

Now build the project from source with:

```cmake ..```

```make```

```./quantom_exec```
